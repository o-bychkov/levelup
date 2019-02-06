FROM maven
WORKDIR /usr/share
ARG git_url
RUN git clone "${git_url}" app
WORKDIR /usr/share/app
CMD ["mvn", "package"]
