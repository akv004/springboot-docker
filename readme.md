docker build -t springboot-app .

docker run -t -i --rm -p 8280:8080 springboot-app  bash
