# Build image

VERSION=7.3.1611

all: build

init:
	docker pull centos:$(VERSION)

build: init
	docker build -t thanandorn/vagrant-centos:$(VERSION) .

