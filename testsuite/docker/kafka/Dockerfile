FROM quay.io/strimzi/kafka:0.31.1-kafka-3.2.3

USER root
RUN rm -rf /opt/kafka/libs/bcpkix* /opt/kafka/libs/bcprov* /opt/kafka/libs/keycloak*
USER kafka
