#FROM microsoft/aspnetcore:1.1
#FROM microsoft/dotnet:1.1.1-runtime
#FROM microsoft/aspnetcore:1.1.1
#FROM microsoft/aspnetcore:1.0.1
FROM microsoft/dotnet:1.1.1-sdk

ARG source
WORKDIR /app
EXPOSE 80
COPY . .
ENTRYPOINT ["dotnet", "WebApplication2.dll"]
