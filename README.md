# Build a Development Environment in AWS with Terraform

In this project, i used vscode to deploy ec2 instance,along with a vpc, Internet gateway, nat-gateway, security groups, etc, that will serve as a remote development environment that can be logged into directly from vscode.

I utilize several terraform tools and functions such as terraform state, format, replace, console, variables and conditional files, template files and more.

I also used aws userdata and local exe provisioner to bootstrap the ec2 instance and add its connection information to my vscode ssh configuration file, allowing me to modify it for future projects.
