FROM centos:centos7
MAINTAINER vladimir.mezera@gmail.com

LABEL Vendor="Vladimir Mezera"

ENV OPT=/opt/trusted
WORKDIR "${OPT}"

COPY start.sh "/opt/trusted"

EXPOSE 8080
USER 1001
CMD ["/opt/trusted/start.sh"]

