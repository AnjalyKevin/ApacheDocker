# ApacheDocker
Ansible Playbook for Apache Docker Image

Purpose: The YAML file in the repository is useful for the deployment of Apache image to a remote machine.

Instructions: Below are the instructions to execute this YAML file.
          
          In the terminal of the controller node enter the following command:
               git clone https://github.com/AnjalyKevin/ApacheDocker.git
          Then list the folders inside it using the “ls” command.
          Make sure that both files, docker_deploy.yml and README.md, are available.
          Once the files are available below is the command to deploy the docker image:
		          ansible-playbook docker_deploy.yml
          Make sure the user has sudo privileges on the remote machine.
          Add a route to the container from the host machine.

