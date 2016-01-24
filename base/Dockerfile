FROM debian:jessie
MAINTAINER MeteorHacks Pvt Ltd. - changed base img to jessie by Linton Ye

ENV METEORD_DIR /opt/meteord
COPY scripts $METEORD_DIR

RUN bash $METEORD_DIR/init.sh

EXPOSE 80
ENTRYPOINT bash $METEORD_DIR/run_app.sh
