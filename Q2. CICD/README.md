
# solution 

please assume the playbook in `Q1.hostname` folder  has been run on the vm 
to ensure minikube is running on the host

so we have a minikube on the vm running with cluster creds setup . 

# CICD 
1. jenkinsfile is configured the job to build and deploy 
2. the stages depict the steps 
3. the configuration minimal and to the point . 

i would have deployed the app to a cluter and verified the working 
please consider the bare minimum needed to deploy an app as gitops model
as discussed in interview.

# improvements:
i would have kept or utilized the helm charts to deploy these apps
no need to use bash logic to use images 

CD can also be a separate job right from each env. 

