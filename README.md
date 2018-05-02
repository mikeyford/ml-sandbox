# tf-sandbox

cd private-aws
ssh -i "private-aws.pem" ubuntu@ec2-18-218-15-164.us-east-2.compute.amazonaws.com

ssh -i "private-aws.pem" -L 8000:localhost:8888 ubuntu@ec2-18-218-15-164.us-east-2.compute.amazonaws.com

localhost:8000

