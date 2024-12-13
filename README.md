# Azure Chaos Engineering Project

Welcome to the **Azure Chaos Engineering** repository! This project evaluates the resiliency and security of Azure cloud infrastructure through fault injection experiments. Key scenarios include disabling logging, exposing storage containers, and opening insecure ports. These tests help identify vulnerabilities and propose robust recovery strategies.

## Key Experiments

1. **Disable Storage Logging**: Simulates missing diagnostics in Azure Storage.
2. **Public Blob Access**: Exposes containers to analyze risks.
3. **Open VM Ports**: Alters NSG rules to evaluate network security.

## Tools and Technologies  

- **Azure CLI**
- **PowerShell Runbooks**
- **Azure Monitor & Log Analytics**
- **KQL (Kusto Query Language)**

## Insights  

Automated fault simulations reveal critical gaps in monitoring and alerting mechanisms, highlighting areas for improved resilience and recovery strategies.
