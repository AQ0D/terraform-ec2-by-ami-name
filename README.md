# terraform-ec2-by-ami-name

Creates EC2 instances by ami name


Prerequisites
``` 
   

    VPCs with "dev" | "qa" | "prod" tags (Sample VPC template)

    tfvars
    
```    
```
environment     =  "dev"
region          =  "us-east-1"	
public_key      =  "ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABAQCjDYBLL/gLcwpl+5Q6HMNibqYu3fi4Asx9qwS9pSvqEkaBCF0Q6Fw0iBS6EoQyFZ8jMUCwT3iBS5nHo5reKDG41idpb4ylc6RF3LmBpczkvj2CrXw12oz8CX7vKf73+o6LUblSJNy+1JAZDAQURLhLA6fYxf4nJ2JnOP9ilnMG24aVR5IW1aDl+JThf8UpVT2fWR8iipsOEWpAfMrSQElhd2qBDODegq6i3iquQmneUbE1f/9JRGdsGHvz6Oq6Hi/quqrN2IwaEgGBkKcnraeYiOqFLiDS0JGifloKAU03WronwiIhpOJ0KDdH2P8G3CpGpDdKHAsfx0PevRM32cjp root@Docker"	
ami_name        =  "apache-0fbab0dd-b6f1-439e-996a-8eb645560390"

```
