This script automates the process of listing all resources in an AWS account for various services like ec2, s3, vpc, iam and etcetera
The user has to specifies the AWS region and service as input, and the script retrieves the resources for that service.
Prerequisites: (1). AWS CLI Installed (2). AWS CLI Configured (3). Script Permissions
Based on the service input, the script lists the corresponding resources using the AWS CLI.
If an invalid service is provided, the script exits with an error message.
