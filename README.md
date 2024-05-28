# aws-cicd
The first stage is to build the CI Pipeline 
Create a role on IAM for code build and add SSMfull access so it has access to docker 
The codepipeline act as an orchestrator . It automatically invokes the aws codebuild when ever there is a cod chnage 
