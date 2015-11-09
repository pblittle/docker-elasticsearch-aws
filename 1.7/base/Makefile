NAME = pblittle/docker-elasticsearch-aws
VERSION = 0.1.1

.PHONY: default
default: run

.PHONY: build
build:
	docker build --rm -t $(NAME):$(VERSION) .

.PHONY: run
run: build
	docker run -d --name elasticsearch $(NAME):$(VERSION)

.PHONY: shell
shell:
	docker exec -ti elasticsearch /bin/bash
