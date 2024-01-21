FROM bitnami/aspnet-core:7.0.15

LABEL author="Andrew Guz"

WORKDIR /opt/WebAPITest1

COPY /bin/Release/net7.0/publish .

EXPOSE 5000

ENTRYPOINT [ "./WebAPITest1" ]
