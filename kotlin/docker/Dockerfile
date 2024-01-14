FROM openjdk:17
RUN microdnf install dnf -y \
    && dnf update -y \
    && dnf install -y \
        curl \
        zip \
    && dnf clean all
WORKDIR /app/
