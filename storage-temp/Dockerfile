FROM openstf/stf:latest

USER dmc
RUN mkdir data && chown stf:stf data
USER stf
VOLUME ["data"]
