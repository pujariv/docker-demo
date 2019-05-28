FROM java:8-jdk-alpine


COPY ./target/frb-mdm-docker-0.0.1-SNAPSHOT.jar /usr/app/

WORKDIR /usr/app

RUN sh -c 'touch frb-mdm-docker-0.0.1-SNAPSHOT.jar'

EXPOSE 4000

ENTRYPOINT ["java","-jar","frb-mdm-docker-0.0.1-SNAPSHOT.jar"]