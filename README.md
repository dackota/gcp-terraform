# gcp-terraform
Set your variables

`export TF_VAR_org_id=ORG_ID
export TF_VAR_billing_account=BILLING_ACCOUNT_ID
export TF_ADMIN=${USER}-terraform-admin
export TF_CREDS=~/.config/gcloud/${USER}-terraform-admin.json`

`export GOOGLE_APPLICATION_CREDENTIALS=${TF_CREDS}
export GOOGLE_PROJECT=${TF_ADMIN}`

`export TF_VAR_project_name=${USER}'s-compute-project
export TF_VAR_region=us-central1`

Finally, plan then apply the configuration:

`terraform plan`
`terraform apply`
