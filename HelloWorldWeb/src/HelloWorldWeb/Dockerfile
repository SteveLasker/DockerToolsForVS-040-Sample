FROM microsoft/aspnetcore:1.0.1
ARG source=.
WORKDIR /app
EXPOSE 80
COPY $source .
ENTRYPOINT dotnet HelloWorldWeb.dll
