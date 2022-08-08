init:
	terraform init
plan:
	terraform plan
delete_terraform:
	rm -rf .terraform.lock.hcl
	rm -rf .terraform
delete-terraform:
	rm -rf .terraform.lock.hcl
	rm -rf .terraform
apply:
	terraform apply -auto-approve
destroy:
	terraform destroy -target=module.kubernetes-addons -auto-approve
	terraform destroy -target=module.aws_controllers -auto-approve
	terraform destroy -target=module.eks_blueprints -auto-approve
	terraform destroy -auto-approve
	
