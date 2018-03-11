# aws-iamroles
STS assume role policies to demonstrate cloud security issue

* assume_role_policy allows any AWS account to assume a role into the account in which this policy is created
* server_policy is an example of a policy intended for an orchestration server to assume
* route53_policy is an example of an additional policy assumed by the orchestration server
* correct_sts_policy should replace the badly written assume_role_policy as it only allows servers from within the AWS account to assume this role
