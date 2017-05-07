#FROM microsoft/aspnetcore:1.1
FROM microsoft/dotnet:1.1.1-runtime
#FROM microsoft/aspnetcore:1.1.1

ARG source
WORKDIR /app
EXPOSE 80
COPY . .
ENTRYPOINT ["dotnet", "bin/debug/netcoreapp1.1/WebApplication2.dll"]
