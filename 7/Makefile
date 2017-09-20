# Build image

VERSION=7.4.1708

all: build

init:
	docker pull centos:$(VERSION)

build: init
	docker build -t thanandorn/vagrant-centos:$(VERSION) .

