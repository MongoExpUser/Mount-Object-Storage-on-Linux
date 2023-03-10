# Mount-Object-Storage-on-Linux


## Usage
1) The script mounts object storage on Linux/Ubuntu OS directory. 

2) Object storage by various cloud providers include: <br>
    - Amazon S3 (aws_s3) - https://aws.amazon.com/s3/ <br>
    - Linode Object Storage (linode_objs) - https://www.linode.com/products/object-storage/ <br>
    - Backblaze Cloud Storage (b2_cs) - https://www.backblaze.com/b2/cloud-storage.html <br>
    - Google Cloud Storage (gcp_cs) - https://cloud.google.com/storage<br>
    - Azure Blob Storage (Azure_blbs - https://azure.microsoft.com/en-us/products/storage/blobs/ <br>
    - Oracle Object Storage (Oracle_objs) - https://www.oracle.com/cloud/storage/object-storage/<br>
    - etc. <br>


## TO run the Bash script

1) #### Download or clone the following file, from this repo, into the current working directory (CWD) on the Linux/Ubuntu OS machine: <br>
   - Bash script - mount-object-storage.sh<br>
   
2) #### Fill in relevant input variables (line 22-27 of the script) at the top of the script including: <br>
   - clean_system_confirm
   - mount_storage_confirm
   - mount_dir
   - bucket_name
   - provider_url
   - credentials

4) #### Then set permssion on the script and run the script, assuming sudo access: <br>
   - set permission <br>
   sudo chmod +x mount-object-storage.sh
   - run <br>
   ./mount-object-storage.sh


# License

Copyright © 2015 - present. MongoExpUser

Licensed under the MIT license.
