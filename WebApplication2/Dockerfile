FROM microsoft/aspnetcore-build

ARG source
WORKDIR /publish
EXPOSE 5000
COPY . .
ENTRYPOINT ["dotnet", "WebApplication2.dll"]
#ENTRYPOINT ["dotnet", "run"]
