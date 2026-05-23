<h1>My Projects</h2>

- [**Mapping Industry Concentration with LinkedIn Job Data**](https://github.com/david-p-sorensen/Location-Quotient-Visualization/blob/main/README.md)
  - Developed an automated data pipeline using **Python** and the OpenAI API to process and classify **124,000+ jobs** posted on LinkedIn, achieving granular industry and ownership categorization across all U.S. states
  - Engineered and maintained a comprehensive **Excel** dataset containing **9,000+ data points** tracking state-level employment metrics and industry concentration parameters
  - Built an interactive web application in **R** using **Shiny** and **Plotly** libraries to create dynamic heat maps with custom color scaling and hover-based state analytics


  
- [**AWS Hosted Portfolio Website**](https://github.com/david-p-sorensen/aws-cloud-resume)
  - Built a static website with **HTML**, **CSS**, and **JavaScript**, hosting it with an Amazon S3 bucket
  - Deployed the website as a **CloudFront** distribution, using an HTTPS protocol, and created an alternate domain name using **Route 53**
  - Created a **DynamoDB** table to track the number of website views which gets updated with a **Lambda** function written in **Python** and is displayed on the website using JavaScript
  - Implemented Infrastructure as Code with **Terraform** for programmatic access to the AWS console
  - Maintain **CI/CD** by pushing changes to the website with GitHub

  

- [**Azure Sentinel Honeypot SIEM**](https://github.com/david-p-sorensen/Azure-Sentinel-Honeypot-SIEM)

  - Used custom **PowerShell** script to extract metadata from Windows Event Viewer to be forwarded to third party API that derives geolocation data
  - Configured **Log Analytics Workspace** in Azure to ingest custom logs containing geographic info
  - Configured Custom Fields in Log Analytics Workspace with the intent of mapping this data in Sentinel
  - Configured Azure Sentinel (Microsoft’s cloud SIEM) workbook to display global attack data (RDP brute force) on world map according to physical location and magnitude of attacks


- [**Active Directory Home Lab**](https://github.com/david-p-sorensen/Active-Directory-Home-Lab)

  - Simulated a Windows networking environment used by organizations by housing Active Directory on a virtual machine as a domain controller
  - Created two network adaptors on domain controller for the internet and internal clients
  - Assigned IP addressing, configured **NAT**, routing, and **DHCP** for the internal server
  - Created 1,000 users on the internal server with a **PowerShell** script
  - Connected another virtual machine to the internal server and logged in as one of the users
