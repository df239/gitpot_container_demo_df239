# gitpot_container_demo_df239

https://gitpod.io/#https://github.com/df239/gitpot_container_demo_df239

git status

git diff

git commit -a
 
git push

docker build .

docker images

docker build --tag (container name) .

docker run (container name)

docker run (container name) /bil/sh

docker run -it (container name) /bin/sh --> interactive mode

docker ps -a

docker run --rm -it (container name) /bin/sh

docker rm (conainer ID)

curl (URL) -O --> opens website URL: raw.githubusercontent.com/calaldees/TeachProgramming/master/teachprogramming/static/projects/net/http_server.py

docker run --rm -it --publish 8000:8000 (container name)

docker run --rm -it --publish 8000:8000 --entrypoint /bin/sh (container name)