TODAY := $(shell date '+%Y.%m.%d')

.PHONY: build

build:
	docker build --build-arg=TODAY=$(TODAY) --progress=plain --tag="minio:$(TODAY)-debian-13" .
