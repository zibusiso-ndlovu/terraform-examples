[![Maintained by Zibusiso Edwin Ndlovu]](https://github.com/zibusiso-ndlovu/terraform-examples)
![Terraform Version](https://img.shields.io/badge/tf-%3E%3D0.12.0-blue.svg)

# An Introduction to Terraform Sample Code

This repo contains the sample code for various infrastructure provisioning in AWS, GCP and AZURE using Terraform 

1. [How to Manage Terraform State](https://www.terraform.io/docs/backends/types/s3.html)
    * [terraform-s3-backend](./terraform-s3-backend): Create an S3 bucket and DynamoDB table to use as a Terraform backend. 
       

## Quick start

**Note**: These examples deploy resources into your AWS account. Although all the resources should fall under the
[AWS Free Tier](https://aws.amazon.com/free/), it is not our responsibility if you are charged money for this.

1. Install [Terraform](https://www.terraform.io/).
1. Set your AWS credentials as the environment variables `AWS_ACCESS_KEY_ID` and `AWS_SECRET_ACCESS_KEY`.
1. `cd` into one of the example folders.
1. Run `terraform init`.
1. Run `terraform apply`.
1. After it's done deploying, the example will output URLs or IPs you can try out.
1. To clean up and delete all resources after you're done, run `terraform destroy`.

## License

Please see [LICENSE.txt](/LICENSE.txt) for details on how the code in this repo is licensed.

