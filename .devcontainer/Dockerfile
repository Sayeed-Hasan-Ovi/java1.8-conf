FROM mcr.microsoft.com/devcontainers/base:alpine

# Install dependencies for sdkman and Java
RUN apk add --no-cache curl zip unzip bash ca-certificates openjdk8

# Set JAVA_HOME and update PATH
ENV JAVA_HOME="/usr/lib/jvm/java-1.8-openjdk"
ENV PATH="${JAVA_HOME}/bin:${PATH}"

# Verify installation
RUN java -version