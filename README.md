# Multi-container Docker Compose in Web App for Containers
This custom image is based on the 'official image' of [WordPress from Docker Hub](https://hub.docker.com/_/wordpress/).

The following changes have been made in this custom image:
- Explicitly uses WordPress 4.9.5, PHP 7.2 and Apache 4.
- Adds PHP extension for Redis v4.0.2.
- Adds Baltimore Cyber Trust Root Certificate file for SSL to MySQL.
- Uses WordPress plugin for Redis Cache.
- Adds WordPress environment variables for SSL connectivity to Azure DB for MySQL.
- Adds WordPress environment variables for connectivity to Redis.

## Setting up multi-container configuration for Web App for Containers
Follow the [tutorial](https://docs.microsoft.com/en-us/azure/app-service/containers/tutorial-multi-container-app) here.

## Contributing
This project welcomes contributions and suggestions. Most contributions require you to agree to a Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us the rights to use your contribution. For details, visit https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the Microsoft Open Source Code of Conduct. For more information see the Code of Conduct FAQ or contact opencode@microsoft.com with any additional questions or comments.
