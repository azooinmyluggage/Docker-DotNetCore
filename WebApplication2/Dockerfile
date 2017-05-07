#FROM microsoft/aspnetcore:1.1
#FROM microsoft/dotnet:1.1.1-runtime
#FROM microsoft/aspnetcore:1.1.1
#FROM microsoft/aspnetcore:1.0.1
#FROM microsoft/dotnet:1.1.1-sdk
FROM microsoft/aspnetcore

ARG source
WORKDIR /app
EXPOSE 5000
COPY . .
ENTRYPOINT ["dotnet", "WebApplication2.dll"]
