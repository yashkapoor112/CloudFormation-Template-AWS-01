# CloudFormation-Template-AWS-01

This is a CloudFormation template to automate the creation of an EC2 instance and some other resources on Amazon AWS.

It also creates a WebSecurityGroup.

The default Instance Type(t2.micro) is free tier enabled.

After the creation this template also installs an apache server onto the instance created.

The instance created uses SSH encyptoion to connect so make sure you have the same .ppk file both ways.
