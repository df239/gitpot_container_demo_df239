DOCKER_IMAGE:=http_server_java

help:
	#Help goes here

build:
	docker build --tag ${DOCKER_IMAGE} .

run:
	docker run --rm -it --publish 8000:8000 ${DOCKER_IMAGE}

run-volume:
	docker run --rm -it --publish 8000:8000 --volume /workspace/gitpod_test/:/data/ ${DOCKER_IMAGE} /data/

shell:
	docker run --rm -it --publish 8000:8000 --entrypoint /bin/sh ${DOCKER_IMAGE}