## DOCKER BUILD

docker build -t udemy-main .

docker run -d --rm -p 9200:8000 -v $(pwd):/var/www/html --name udemy-main udemy-main