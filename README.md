# Terraform + Packer Automated Using Bashash


# About

This repo consisit of a Bash Script which integrates both Terraform code and Packer code for building an Infra. Terraform code will create Security Group, Key Pair, and EC2 Instance under the dfault VPC, Packer code creates a Custom AMI based on the provision script provided, the bash script also allows you to select which base AMI is required while building the AMI, right now I have included only two options Amazon Linux and Ubuntu.

# Input Data's Required

- Below data's needs to be provided while performing the task
  - Access Key
  - Secret Key
  - Region
  - Instance Type
  - Provision File Path
  - Key-Pair Name
  - List of Ingress Ports

# Outline 

[<img align="center" alt="Unix" width="550" src="https://raw.githubusercontent.com/ManuGeorge96/ManuGeorge96/master/Tools/bash.drawio.png" />][ln]


# How To Use

- ```sh
   git clone https://github.com/ManuGeorge96/terraform-packer-automated-using-bash.git
  ``` 
- ```sh
   cd terraform-packer-automated-using-bash/
  ```
- ```sh
   ./mains.sh  
  ```
  
# Sample Outputs

[<img align="center" alt="Unix" width="750" src="https://raw.githubusercontent.com/ManuGeorge96/ManuGeorge96/master/Tools/1.1.PNG" />][ln]

<br />

[<img align="center" alt="Unix" width="750" src="https://raw.githubusercontent.com/ManuGeorge96/ManuGeorge96/master/Tools/1.2.PNG" />][ln]

<br />

[<img align="center" alt="Unix" width="750" src="https://raw.githubusercontent.com/ManuGeorge96/ManuGeorge96/master/Tools/1.3.PNG" />][ln]

<br />

[<img align="center" alt="Unix" width="750" src="https://raw.githubusercontent.com/ManuGeorge96/ManuGeorge96/master/Tools/1.4.PNG" />][ln]

<br />

[<img align="center" alt="Unix" width="750" src="https://raw.githubusercontent.com/ManuGeorge96/ManuGeorge96/master/Tools/1.5.PNG" />][ln]

<br />

[<img align="center" alt="Unix" width="750" src="https://raw.githubusercontent.com/ManuGeorge96/ManuGeorge96/master/Tools/1.6.PNG" />][ln]







---
## Conclusion

In this tutorial explain how to build AMI using packer tool.

---
### ⚙️ Connect with Me

 <p align="center">
<a href="mailto:aparthan275@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://www.instagram.com/_r.e.b.e.l.z_33/"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/abhiraj-parthan-82038b191"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a> 
<a href="https://www.wppredirect.tk/go/?p=918893532145&m=Abhiraj%20Parthan."><img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white"/></a>
  </a></p>
</div>
