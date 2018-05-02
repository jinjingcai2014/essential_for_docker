FROM microsoft/aspnetcore

MAINTAINER caijingjin

COPY dist  /app

WORKDIR  /app
#对外暴露的端口号
EXPOSE 80/tcp

ENTRYPOINT ["dotnet","ExampleApp.dll"]
