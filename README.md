# aws-ec2-migration
aws-ec2-migration when windows license needs to be updated from BYOL to non-BYOL

Ansible script will perform below mentioned steps to update AWS Windows EC2 license. (It will retain same IP)

![image](https://user-images.githubusercontent.com/29974760/126468696-af15cc40-d398-4a9e-96a6-66c88b9c44c8.png)


**Script 1:** ec2-kms-migration.yaml (This will update ec2 instance from BYOL to Non-BYOL)

**Script 2:** update-ec2-win-lic.yaml (This will update windows license)
FYI: Above script will override activation from Active directory based auth to KMS based auth. (update this in case not required)


**Note:** Tags will have to update manually
