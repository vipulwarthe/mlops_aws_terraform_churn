# MLOps using Terraform in AWS
This project includes the codes and configurations to build a MLOps pipeline in AWS with Terraform. The machine learning model is built to predict customer churn and deployed with Flask API and Docker using AWS services. 

This is the blog where I explained the building process : https://medium.com/@farsim/machine-learning-deployment-in-docker-and-mlops-in-aws-using-terraform-6d526552f33f

Connect with me through Linkedin : https://www.linkedin.com/in/mahmood-hossain-farsim/?lipi=urn%3Ali%3Apage%3Ad_flagship3_feed%3Bdd1mY4MeSN66TfADMa4xHA%3D%3D

![alt text](https://github.com/farsim-hossain/mlops_aws_terraform_churn/blob/main/mlops_terraform_architecture.gif)


    1  sudo apt-get update && sudo apt-get upgrade -y
    2  sudo apt install python3-venv -y
    3  python3 -m venv venv
    4  source venv/bin/activate
    5  mkdir mlproject
    6  git clone https://github.com/vipulwarthe/mlops_aws_terraform_churn.git
    7  ls
    8  rmdir mlproject/
    9  cd mlops_aws_terraform_churn/
    10  ls
    11  cd FlaskApplication/
    12  LS
    13  ls
    14  pip install -r requirements.txt 
    15  sudo apt-get install graphviz
    16  sudo apt-get install xdg-utils
    17  pip uninstall lightgbm
    18  pip install lightgbm
    19  sudo apt-get install libgomp1
