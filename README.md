<div align="center">
  <h1><strong>Azure Chaos Engineering Project </strong></h1>
</div>

This project evaluates the resiliency and security of Azure cloud infrastructure through fault injection experiments. Key scenarios include disabling logging, exposing storage containers, and opening insecure ports. These tests help identify vulnerabilities and propose robust recovery strategies.

## Key Experiments

1. **Disable Storage Logging**: Simulates missing diagnostics in Azure Storage.
2. **Public Blob Access**: Exposes containers to analyze risks.
3. **Open VM Ports**: Alters NSG rules to evaluate network security.

## Tools and Technologies  

- **Azure CLI**
- **PowerShell Runbooks**
- **Azure Monitor & Log Analytics**
- **KQL (Kusto Query Language)**

## Results  

- **Storage Logging**: Disabling logging revealed gaps in alerting mechanisms, showing risks of undetected misconfigurations.
- **Public Blob Access**: Exposed sensitive data due to improper access control, emphasizing the need for Azure Policy enforcement.
- **Open Ports**: Increased attack surface by allowing insecure traffic, highlighting vulnerabilities in network configurations.

The findings demonstrate critical gaps in Azure's native alerting systems and propose actionable improvements to enhance resilience.
