# Terraform Provisioner

## What is Provisioner?

Provisioners can be used to model specific actions on the local machine or on a remote machine in order to prepare servers or other infrastructure objects for service.

- Terraform includes the concept of provisioners as a measure of pragmatism, knowing that there will always be certain behaviors that can't be directly represented in Terraform's declarative model.

Passing data into virtual machines and other compute resources

- When deploying virtual machines or other similar compute resources, we often need to pass in data about other related infrastructure that the software on that server will need to do its job.

The various provisioners that interact with remote servers over SSH or WinRM can potentially be used to pass such data by logging in to the server and providing it directly, but most cloud computing platforms provide mechanisms to pass data to instances at the time of their creation such that the data is immediately available on system boot

## What are Generic Provisioners?

### There are 3 types of Provisioners

- File
- Remote Exec
- Local Exec

# File 
<img width="953" alt="file_prov" src="https://user-images.githubusercontent.com/108756145/223218152-33fd48bf-8e43-489a-b974-95037baa83b4.png">


# Remote Exec
<img width="957" alt="remote exec prov" src="https://user-images.githubusercontent.com/108756145/223218205-875ef9df-6b4d-48ca-a529-856bfaab5e2f.png">


# Local Exec
<img width="1028" alt="local exec prov" src="https://user-images.githubusercontent.com/108756145/223218242-798f0d0b-fbec-46ab-af24-ab016887dcfd.png">
