```
FROM debian:jessie

RUN apt-get update

RUN apt-get install -y git vim

CMD ["echo","hello world"]
```


