#FROM microsoft/aspnetcore:1.1
FROM microsoft/aspnetcore-build
ARG source
WORKDIR /app
EXPOSE 80
COPY . .
ENTRYPOINT ["dotnet", "WebApplication2.dll"]
