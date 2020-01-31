# Build a back-end API by Using Azure Storage and API Apps

- Create the WebAPI
  - dotnet new webapi --name ImageAPI -f netcoreapp2.2
  - dotnet add package WindowsAzure.Storage

- Build a front-end web application by using Azure Web Apps
  - dotnet new webapp --name ImageWeb -f netcoreapp2.2
  - dotnet add package Flurl
