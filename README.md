# Ansible Role: app_iiq_remove
Removes an IIQ Docker container

## Requirements

You must have Docker installed and IdentityIQ deployed to Docker.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    tomcat_log_volume_name: sandbox_iiq_tomcat_logs

Name of the docker volume for the tomcat logs.  Usually overriden in the format of <company name>_iiq_tomcat_logs

    tomcat_work_volume_name: sandbox_iiq_tomcat_work

Name of the docker volume for the tomcat work directory.  Usually overriden in the format of <company name>_iiq_tomcat_work

    tomcat_catalina_volume_name: sandbox_iiq_tomcat_catalina

Name of the dockder volume for the catalina volume.  Usually overriden in the format of <company name>_iiq_tomcat_catalina

    tomcat_temp_volume_name: sandbox_iiq_tomcat_temp

Name of the docker volume for the tomcat temporary logs.  Usually overriden in the format of <company name>_iiq_tomcat_temp

    network_name: sandbox_iiq

Name of the docker network to attach the generated containers to.  Usually overriden in the format of <company name>_iiq

    iiq_container_name: sandbox-iiq

Name of the generated docker container.  Usually overriden in the format of <company name>-iiq

    remove: false

Flag to determine if the accelerator pack is being installed.

## Dependencies

None.

