TODAY := $(shell date '+%Y.%m.%d')

.PHONY: build

build:
	docker pull docker.io/bitnami/minideb:trixie
	docker build --build-arg=TODAY=$(TODAY) --progress=plain --tag="minio:$(TODAY)-debian-13" .
