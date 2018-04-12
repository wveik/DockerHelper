docker run -p 80:80 aspnetapp
docker build -t aspnetapp .
docker rmi -f aspnetapp



    docker login --username username --password password

    docker tag my-image username/my-repo

    docker push username/my-repo

