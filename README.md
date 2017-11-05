# OS2_HW2
  
> - DEMO @https://youtu.be/uPj_6IRhBSY
  
Create load balancer with auto scaling
> Simple web app with high cpu usage

Features
> - create load balancer
> - scale up's policy
> - scale down's policy

Prerequisite  
> - create rsa key (e.g. using puttykeygen)
> - AWS access and secret key
> - locust
> - terraform

Create RSA KEY
>  follow this instruction @https://docs.joyent.com/public-cloud/getting-started/ssh-keys/generating-an-ssh-key-manually/manually-generating-your-ssh-key-in-windows

Create AWS acress and secret key
>  follow this instruction @http://docs.aws.amazon.com/general/latest/gr/managing-aws-access-keys.html

Installing Locust
>  pip install locustio (Must have python pip)

Installing terraform
> follow this instruction @https://www.terraform.io/intro/getting-started/install.html

How to
> - check everything in terra.tf
> - if you don't want to use Target group ARN use terra in TerraformWithLoadBalancer
> - else you have to create own load balancer with target group
> - use "terraform plan" in terminal or CMD
> - use "terraform apply" in terminal or CMD
> - if you want to test auto scaling use locust with command "locust --host=${web url}"


Operation System 2 Homework2  
created by TheTonG