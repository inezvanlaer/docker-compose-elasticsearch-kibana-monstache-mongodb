FROM mongo

RUN echo "rs.initiate();" > /docker-entrypoint-initdb.d/replica-init.js

EXPOSE 27017

CMD [ "--replSet", "rs0" ]
