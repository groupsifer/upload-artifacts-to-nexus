# upload artifacts to nexus repository using Jenkins CICD

# Pre-Requisites:
    - Install Java
    - Install Git
    - Install Maven
    - Install Nexus
    - Install Jenkins
# Install Nexus
  [Nexus Installation](https://github.com/cloudtechmasters/nexus-installation-linux/blob/master/README.md)
# Add Plugins to jenkins
    - Nexus Artifact Uploader
    - Pipeline Utility Steps
# Integrations with Jenkins
    - Git
    - Maven
# Create credentials in jenkins for nexus
    - Please give ID name as "nexus-user-credentials"
# Create Pipeline with Jenkins pipeline code
    Edit Environment details of Nexus
# Need to do scriptApproval
    Path: Manage Jenkins --> In-Process Script Approval 
    Go to this place aprove it for the first time
    It will contain below content based on your project
    --------------------------------------------------------------
    	method org.apache.maven.model.Model getPackaging
    --------------------------------------------------------------
