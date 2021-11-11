FROM microsoft/aspnetapp:latest
ARG source
WORKDIR /app
EXPOSE 80
COPY ${source:-obj/Docker/publish} .
ENTRYPOINT ["dotnet", "MyHealth.Web.dll"]
