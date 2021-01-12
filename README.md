# Mathgarage Setup Instructions

1. git clone https://github.com/jaichenchlani/mathgarage.git
2. git clone https://github.com/jaichenchlani/mathgarage-build.git
3. Upload the credentials-prod.json and credentials-sandbox.json files to the mathgarage/keys folder
4. Navigate to mathgarage-build directory i.e. _cd mathgarage-build_
4. Update **_buildconfig.json_** 
5. Execute **./mathgaragebuild.sh buildconfig.json**

### _buildconfig.json_
1. pull_latest_code_from_github: 0 or 1. 0 indicates no code pull from github, 1 indicates run "git pull origin master".
2. build_folder: Path of the build folder.
3. app_name: App Name
4. app_version: App Version
5. gcp_project_id: GCP Project ID
6. gcr_image_prefix: GCR Image Prefix
7. build_flag: 0 or 1. 0 indicates no build, 1 indicates build.
8. deploy_flag: 0 or 1. 0 indicates no Deploy, 1 indicates Deploy to App Engine.
