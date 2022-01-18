FROM hello-world

RUN apt-get update

CMD ["echo","Hello World...! From my first docker image"]

ENV name desktop
