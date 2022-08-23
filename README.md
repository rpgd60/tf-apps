## Terraform Cloud VCS Integration with GitHub 
This repo is intended to serve as an "umbrella" repository for multiple applications (app1, app2, etc.)
Each application will have multiple environments (dev, prod)

Intended to explore the Terraform OAuth-based VCS integration with Github

Explore if a Workspace can point to a specific "folder" (e.g. app2/dev,  app3/prod)
This would be an alternative to having dedicated repos for each combination (e.g. repos app1-dev, app1-prod, etc.)

In app2
- All variables except app_name are defined in variables.auto.tfvars
    - Explore if TF Cloud does not prompt for these variables to be created in the workspace
In app3
- All variables except app_name AND environment are defined in variables.auto.tfvars
    - Explore if TF Cloud does not prompt for these variables to be created in the workspace

