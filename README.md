# Inbound/outbound traffic for Azure Services behind Private Endpoints

## Traffic: inbound through private endpoint and optinal outboud through VNET integration

- WebApp
- Logic Apps
- Function App

> **Note:** Check the App Service Plan and SKU. Not all plans support Private Endpoint and VNET integration

## Traffic: inbound/outbound

- Key Vault
- SQL (Firewall allows IPs)
- CosmosDB
- PostgreSQL
  - **Note:** Can be VNET integrated with Flexible Server
- Service Bus
- Redis Cache 
  - **Note:** Redis can be VNET integrated
- App Configuration
- SignalR
- Event Grid

## Traffic: inbound/outboud through Azure Monitor Private Link Scope

- AppInsights
- Log Analytics

> **Note:** inbound and outboud private traffic can be set independently
