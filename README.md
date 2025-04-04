# lab13-acit4640
1. (Tuan) Thanh Nguyen
2. Marcus Su
3. Refeel Geelani

## Questions
1. When is the state file created?
The state file (terraform.tfstate) is created after running terraform apply for the first time.

2. When is the lock file present?
The lock file is present while a Terraform operation (like apply or plan) is running (before type yes).

3. Is the lock file always in the bucket after it is created?
No, the lock file is temporary and only exists while a Terraform command is executing. It disappears when the operation is done (after type yes).

![1](https://github.com/user-attachments/assets/9c440e4a-c4b4-47a9-b1b4-2b0b5c916fdd)
![2](https://github.com/user-attachments/assets/dd789f66-c457-44a3-b28b-6fb1baae978f)
