# Mathgarage Setup Instructions

1. git clone https://github.com/jaichenchlani/mathgarage.git
2. git clone https://github.com/jaichenchlani/mathgarage-build.git
3. Upload the credentials-prod.json and credentials-sandbox.json files to the mathgarage/keys folder
4. Update buildconfig.json 
5. Execute **./mathgaragebuild.sh buildconfig.json**

### _buildconfig.json_
#### pull_latest_code_from_github: 0 or 1. 0 indicates no code pull from github, 1 indicates run "git pull origin master".
#### build_folder: Path of the build folder.
#### app_name: App Name
#### app_version: App Version
#### gcp_project_id: GCP Project ID
#### gcr_image_prefix: GCR Image Prefix
#### build_flag: 0 or 1. 0 indicates no build, 1 indicates build.
#### deploy_flag: 0 or 1. 0 indicates no Deploy, 1 indicates Deploy to App Engine.
