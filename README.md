# GCP Cloud Storage - Best Practices in Building a Data Lake on GCP

## Data Security
- Disable **public access** only when necessary to make data available publicly, Enable it when u want to make avaialale for anyone to use
- Use **Google-Managed Encryption Keys** for default encryption managed by Google.
- Enable **Customer-Managed Encryption Keys (CMEK)** for sensitive data.
- Enable **Customer-Supplied Encryption Keys (CSEK)** for high sensitive data.
- Configure **bucket retention policies** to prevent premature deletion of critical data.
