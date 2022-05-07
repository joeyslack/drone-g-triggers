# Azure Storage Triggers

To store Azure trigger functions. See the azure portal: `https://portal.azure.com/#blade/WebsitesExtension/FunctionsIFrameBlade/id/%2Fsubscriptions%2Fec4feacc-5344-4e52-9115-559b961d2bc3%2FresourceGroups%2Fgatheruploader%2Fproviders%2FMicrosoft.Web%2Fsites%2Fgather-upload-functions`

## Getting Started

For local development, I highly encourage you to use VSCode, seriously, it will save a ton of time. Install the `Azure Functions` package once you do. This will allow you to test, debug, and monitor your apps, while listening to real storage buckets.

It will install appropriate dependencies upon launch, but if not:

`brew tap azure/functions
brew install azure-functions-core-tools@3`

## Debugging

Use the `Azure Functions` package to debug. It should resolve dependencies and attach debugger

## Deployment

Use the VSCode `Azure Functions` package to deploy, using deploy functionality per function. 