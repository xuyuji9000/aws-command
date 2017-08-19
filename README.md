# aws command

Command demo for aws cli.

## Resources

- Images

  Ubuntu 16.04 `ami-d28a53bc`

- Instance Types

  t2.nano   1cpu  0.5G
  t2.micro  1cpu  1G
  t2.small  1cpu  2G

## Command Structures

- Create EC2 Instances

  `aws ec2 run-instances --image-id ami-xxxxxxxx --count 1 --instance-type t1.micro --key-name MyKeyPair --security-groups my-sg`

- Add ingress rules

  `aws ec2 authorize-security-group-ingress --group-name MySecurityGroup --protocol tcp --port 22 --cidr 203.0.113.0/24`

- Get instance information
  `aws ec2 describe-instances --filters "Name=instance-state-name,Values=running"`
