FROM microsoft/nanoserver:latest

ENV JAVA_PKG=server-jre-8u171-windows-x64.tar.gz \
    JAVA_HOME=C:\\jdk1.8.0_171

ADD $JAVA_PKG /

RUN setx /M PATH %PATH%;%JAVA_HOME%\bin
