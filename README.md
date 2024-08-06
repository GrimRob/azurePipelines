# GrimRob's Azure Pipelines Collection

I have assembled this small YAML pipeline collection for Azure DevOps with GitHub support.

1. [buildDotNet.yml](./buildDotNet.yml) - Compiles a .NET solution (with NuGet libraries for your bespoke feed).
1. [dockerPush.yml](./dockerPush.yml) - Builds and pushes a Docker image to GitHub CR.
1. [dockerPushWithNuget.yml](./dockerPushWithNuget.yml) - Builds using a [nuget.config](./nuget.config) file which uses your Azure Artifact feed and a PAT, and pushes a Docker image to GitHub CR.
