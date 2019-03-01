FROM microsoft/dotnet:2.1-sdk

WORKDIR /app

COPY ./src/publish .

ENTRYPOINT ["dotnet", "src.dll"]