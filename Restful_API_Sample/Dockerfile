FROM microsoft/aspnetcore:2.0
ARG source
WORKDIR /app
EXPOSE 5050
COPY ${source:-obj/Docker/publish} .
ENTRYPOINT ["dotnet", "Restful_API_Sample.dll"]
