FROM progrium/buildstep
MAINTAINER Dragan Milic <dragan@netice9.com>
RUN apt-get -y install nginx
RUN mkdir /app
RUN git clone https://github.com/draganm/regenwolke_rails app
RUN /build/builder
ENTRYPOINT /bin/bash -c "/start web"
