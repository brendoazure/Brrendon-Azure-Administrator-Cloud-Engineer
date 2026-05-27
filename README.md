📘 Azure Storage Account Project — Data Protection & Lifecycle Automation
📌 Overview
This project demonstrates real‑world Azure Storage administration, including:

Storage account creation

Container structure (raw, processed, archive)

Data protection configuration

Soft delete testing

Lifecycle management automation

Blob recovery

Cost‑optimised data governance

This is a core skill for Azure Administrators and Cloud Engineers
🏗️ Architecture
Code
Storage Account (StorageV2)
│
├── raw
│   └── uploaded files (source data)
│
├── processed
│   └── transformed data (future use)
│
└── archive
    └── long‑term retention
    🔐 Data Protection
Enabled features:

✔️ Soft delete for blobs

✔️ Soft delete for containers

✔️ Change feed

✔️ Versioning (conceptually demonstrated)

These settings protect against accidental deletion and support auditability.

🧪 Soft Delete Test
Uploaded a file into raw


Deleted the file
Verified it appeared under Deleted blobs

Restored it using Undelete

This confirms recovery works as expected

⚙️ Lifecycle Management Rule
Rule name: move-old-data-to-archive

Actions configured:

Move to cool tier after 0 days

Move to archive tier after 1 day

Delete blob versions after 7 days

Delete base blobs after 30 days

This simulates automated cost optimisation and long‑term retention.

🎯 Skills Demonstrated
Azure Storage administration

Data protection & governance

Blob lifecycle automation

Cost optimisation

Real‑world Azure Admin workflow

Documentation & cloud project delivery

📂 Status
Project completed as part of my Azure Administrator learning path.






