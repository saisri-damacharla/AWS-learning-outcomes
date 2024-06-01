# Launching a simple python app on EC2 instance in your VPC.
Step-1: Create a simple VPC
<img width="881" alt="01 create vpc" src="https://github.com/saisri-damacharla/AWS-learning-outcomes/assets/162766163/bb29009d-7f8b-43d0-8c3c-462950081bb4">

Step-2: Launch an EC2 instance with the created VPC and enable the "assign public IP-address" 
<img width="841" alt="02 launch ec2" src="https://github.com/saisri-damacharla/AWS-learning-outcomes/assets/162766163/aea0f96e-dff4-4e6a-915d-f33e59398ce4">

Step-3: Deploy simple python server on port 8000
<img width="449" alt="03 launch python app" src="https://github.com/saisri-damacharla/AWS-learning-outcomes/assets/162766163/0f63255e-ce86-4659-b4da-35126b8e6fc4">

step-4: Access the python server from internet
<img width="474" alt="04 before SG" src="https://github.com/saisri-damacharla/AWS-learning-outcomes/assets/162766163/09d4c91e-dd8e-4dd7-8de1-98ac9e0f9c9f">

Step-5: Check NACL of VPC if it's allowing all traffic or not
<img width="857" alt="05 check NACL traffic" src="https://github.com/saisri-damacharla/AWS-learning-outcomes/assets/162766163/3446ca7c-ba6a-4f4a-a920-be2d6c98c1ca">

Step-6: Check SG and modify traffic rules accordingly
<img width="869" alt="06 Modify SG" src="https://github.com/saisri-damacharla/AWS-learning-outcomes/assets/162766163/d549420d-7445-438f-85a7-9ebf5b9771b3">

Step-7: Access the server from Internet 
<img width="542" alt="07 after SG" src="https://github.com/saisri-damacharla/AWS-learning-outcomes/assets/162766163/fe20b671-ff4b-49d8-a44a-cf0c2a5128a3">
