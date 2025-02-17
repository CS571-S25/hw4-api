build
```bash
docker build . -t ctnelson1997/cs571-s25-hw4-api
docker push ctnelson1997/cs571-s25-hw4-api
```

run
```bash
docker pull ctnelson1997/cs571-s25-hw4-api
docker run --name=cs571_s25_hw4_api -d --restart=always -p 58104:58104 -v /cs571/s25/hw4:/cs571 ctnelson1997/cs571-s25-hw4-api
```