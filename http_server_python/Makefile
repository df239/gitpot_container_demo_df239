help:
	#build
	#run
	#shell

build:
	docker build --tag my_container .

run:
	docker run --rm -it --publish 8000:8000 my_container

shell:
	docker run --rm -it --publish 8000:8000 --entrypoint /bin/sh my_container