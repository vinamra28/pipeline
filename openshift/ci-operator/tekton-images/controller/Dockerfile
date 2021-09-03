# Do not edit! This file was generated via Makefile
FROM registry.access.redhat.com/ubi8/ubi-minimal:latest

ENV KO_DATA_PATH=/kodata
ADD ${bin} /ko-app/${bin}
COPY HEAD ${KO_DATA_PATH}/
COPY refs ${KO_DATA_PATH}/

ENTRYPOINT ["/ko-app/controller"]
