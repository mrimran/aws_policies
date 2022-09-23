# Ready to use AWS Policies
In this repo I'm going to place the AWS policies that can save other's time.

## iam_manage_policies_policy.json
This file can help you share the policies management to other people. 
Normally development needs that to create polices for RDS, Web Server, RDS etc.

## rds_databases_access_policy.json
Using this policy file you can share full-access to the RDS service including Databases Management.
Again development teams needs such permissions to work with the databases.


## How to use?
- Go in `IAM` >> `Policies` >> `Create policy`
- Click on `JSON` tab
- Copy the `JSON` from these files and `paste` it there
- Click Next and finish these steps and create the policy.

Once policy is created:
- Click on policy
- Click on `Policy usage`
- Click on `Attach`
- Choose required Role, group or user and click on `Attach policy`.

**Note: You can tweak as per your needs. I created these files, because these step take time when are done for the first time.**
