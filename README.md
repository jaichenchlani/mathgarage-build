# MathGarage Build Scripts
The script will need the following json config file as input. 
{
    "pull_latest_code_from_github": 0,
    "build_folder": "localdata/software/business/mathgarage",
    "app_name": "mathgarage",
    "app_version": "v0.982",
    "gcp_project_id": "mathgarage",
    "gcr_image_prefix": "gcr.io",
    "build_flag": 1,
    "deploy_flag": 1
}

#pull_latest_code_from_github: 0 or 1. 0 indicates no code pull from github, 1 indicates run "git pull origin master".
#build_folder: Path of the build folder.
#app_name: App Name
#app_version: App Version
#gcp_project_id: GCP Project ID
#gcr_image_prefix: GCR Image Prefix
#build_flag: 0 or 1. 0 indicates no build, 1 indicates build.
#deploy_flag: 0 or 1. 0 indicates no Deploy, 1 indicates Deploy to App Engine.
