# Setup for SQL Server on Docker on Apple Silicon

## Requirements

- Docker image
- [Azure Data Studio](https://docs.microsoft.com/ja-jp/sql/azure-data-studio/download-azure-data-studio?view=sql-server-ver15#download-azure-data-studio)
- or [a VSCode SQL Server Extension](https://marketplace.visualstudio.com/items?itemName=ms-mssql.mssql)

## Setup the container

Run `./runner start`

## How to connect using Azure Data Studio

1. `Add connection`
2. Enter `Connection Details`
   - `Connection Type`: `Microsoft SQL Server`
   - `Server`: localhost
   - `User name`: sa
   - `Password`: (the password you set when you created the container)
3. Connect
