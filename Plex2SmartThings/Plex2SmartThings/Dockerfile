FROM microsoft/dotnet:latest
MAINTAINER Mark Groves, mark@markgroves.us
COPY bin/Debug/netcoreapp1.0/publish/ /root/
COPY config.config /
ENTRYPOINT dotnet /root/Plex2SmartThings.dll
