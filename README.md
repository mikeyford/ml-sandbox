# ml-sandbox

aws ec2 start-instances --instance-ids i-0ddc324a28a46caca

aws ec2 describe-instances --instance-ids i-0ddc324a28a46caca --query 'Reservations[].Instances[].PublicDnsName'

ssh -i "ec2-gpu/ec2-gpu.pem" -L 8000:localhost:8888 ubuntu@dns

