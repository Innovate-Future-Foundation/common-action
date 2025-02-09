# common-action

the common workflow actions

## Composite Actions

### Setup terraform with S3 backend

This action setup aws credentials and terraform init with s3 and dynamodb as tfbackend using oidc role assume.

**Action Name** - `setup_tf_aws`

**Required inputs**

- terraform_version
- terraform_dir
- backend_role_arn
- backend_region
- backend_state_bucket
- backend_state_key
- backend_lockid_table
