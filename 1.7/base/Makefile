NAME = pblittle/docker-elasticsearch-aws
VERSION = 0.2.0

DOCKER_IMAGE = $(NAME):$(VERSION)

.PHONY: default
default: run

.PHONY: build
build:
	docker build --rm -t $(DOCKER_IMAGE) .

.PHONY: run
run: build
	docker run -d --name elasticsearch $(DOCKER_IMAGE)

.PHONY: shell
shell:
	docker exec -ti elasticsearch /bin/bash

.PHONY: clean
clean:
	docker rmi $(DOCKER_IMAGE)

.PHONY: tag
tag:
	docker tag $(DOCKER_IMAGE) $(NAME):latest

.PHONY: release
release:
	docker push $(NAME)
