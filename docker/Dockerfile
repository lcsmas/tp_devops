FROM openjdk
ENV POSTGRES_PASSWORD=foo123
ENV POSTGRES_USER=admin
ENV POSTGRES_DB=127.0.0.1/tp_devops
COPY . .
CMD java -Ddatabase.url=$POSTGRES_DB -Ddatabase.username=$POSTGRES_USER -Ddatabase.password=$POSTGRES_PASSWORD -jar tp-docker-1.0.0.jar

