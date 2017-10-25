# Build Stage
FROM microsoft/dotnet:2-sdk

WORKDIR /integration

# copy
COPY integration.csproj .
RUN dotnet restore

COPY . .

ENTRYPOINT ["dotnet", "test"]