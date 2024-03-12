# cst8918-w24-h09    LAB9-HYBRID PART



# Summary of steps with Screenshots which I have followed in this lab;


## 1.  As a first step I created main.tf and output.tf files, after initializing terraform I checked terraform plan:

![A screenshot of a computer Description automatically
generated](./Screenshots/1.png){width="6.5in" height="3.89375in"}


## 2.  When I successfully terraform init and terraform plan, I did terraform apply and checed from Azure portal which is all resources are created:


![A screenshot of a computer program Description automatically
generated](./Screenshots/2.png){width="6.5in"
height="3.2597222222222224in"}

## 3.  The content od output which is kubeconfig file's content:

![A screenshot of a computer program Description automatically
generated](./Screenshots/3.png){width="6.5in"
height="3.2597222222222224in"}

## 4.  After successfully deploy for sample-app.yaml file, the output of result:

![A screenshot of a computer program Description automatically
generated](./Screenshots/4.png){width="6.5in"
height="3.2597222222222224in"}

## 5.  After successfully deploy for sample-app.yaml file, the output of "kubectl get nodes" and "kubectl get services":

![A screenshot of a computer program Description automatically
generated](./Screenshots/5.png){width="6.5in"
height="3.2597222222222224in"}

## 6.  After successfully deploy for sample-app.yaml file, the app is working (checked from web portal)

![A screenshot of a computer program Description automatically
generated](./Screenshots/6.png){width="6.5in"
height="3.2597222222222224in"}

## 7.  Do NOT forget to "terraform destroy":

![A screenshot of a computer program Description automatically
generated](./Screenshots/7.png){width="6.5in"
height="3.2597222222222224in"}
