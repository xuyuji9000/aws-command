# aws command

Command demo for aws cli.

## Resources

- Images

  Ubuntu 16.04 `ami-d28a53bc`

- Instance Types

  t2.micro  1cpu  1G
  t2.small  1cpu  2G

## Command Structures

### Create EC2 Instances

`aws ec2 run-instances --image-id ami-xxxxxxxx --count 1 --instance-type t1.micro --key-name MyKeyPair --security-groups my-sg`
