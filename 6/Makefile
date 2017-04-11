# Build image

VERSION=6.9

all: build

init:
	docker pull centos:$(VERSION)

build: init
	docker build -t thanandorn/vagrant-centos:$(VERSION) .

