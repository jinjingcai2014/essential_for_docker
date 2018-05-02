FROM microsoft/aspnetcore

MAINTAINER caijingjin

COPY dist  /app

WORKDIR  /app

EXPOSE 80/tcp

ENTRYPOINT ["dotnet","ExampleApp.dll"]