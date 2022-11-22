# TEMPLATES .gitlab-ci.yml
Templates about .gitlab-ci.yml - FTP / SSH Connections

## Environment Variables
In some templates you could see some variables like these: 
* ``` $DEVELOP_FTP_SERVER ```
* ``` $PRE_RELEASE_FTP_USERNAME ```
* ``` $PRODUCTION_SSH_PRIVATE_KEY ```
* ``` $PRODUCTION_SSH_USER ```
* ``` $PRODUCTION_EC2_IPADDRESS ```
* and so on

In these cases you need to create the environment variables in the gitlab project (docs: https://docs.gitlab.com/ee/ci/variables/#add-a-cicd-variable-to-a-project)
