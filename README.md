# DevOps---Configure-Docker
Configure Docker in RHEL9

# Type the following in the local.repo file where you types the same while configuring yum
In Linux, when you configure Docker, you typically set up a local repository (local.repo) or configure Docker to use a specific registry, such as Docker Hub.

![WhatsApp Image 2023-08-09 at 10 21 17 PM](https://github.com/neelay-16/DevOps---Configure-Docker/assets/135517502/c4e56668-b62a-4308-b2e6-9ef6336cdfed)


# Install Docker
The 'yum install docker-ce' command in Linux is used to install Docker Community Edition (Docker CE), which is a free and open-source containerization platform. Docker allows you to create, deploy, and manage containers, which are lightweight, isolated environments for running applications and services. 

![WhatsApp Image 2023-08-23 at 2 14 38 AM](https://github.com/neelay-16/DevOps---Configure-Docker/assets/135517502/2279dd00-b021-4f96-bc2d-01b367ae5ad2)

# Check that docker is installed properly
There are multiple ways to check that docker is properly installed in our Linux system or not: 
1. To confirm that Docker is installed, you can check its version using the following command:

![image](https://github.com/neelay-16/DevOps---Configure-Docker/assets/135517502/6389312f-7b9f-41bb-b788-2e719e2410ca)

2. You can test Docker by running a simple "Hello World" container using the following command:

![image](https://github.com/neelay-16/DevOps---Configure-Docker/assets/135517502/85eb64fa-ffd1-4514-854f-7d8f94b8d4b6)

If Docker is installed correctly, it will download and run the "Hello World" container, and you'll see a message indicating that your installation appears to be working correctly.
3. You can check the status of the Docker service using the systemctl command. This is especially useful to see if the Docker service is running:

![image](https://github.com/neelay-16/DevOps---Configure-Docker/assets/135517502/1ae41d2a-f621-4d54-ba01-85cf81687026)

If Docker is installed and running, you'll see information about the Docker service, including its status and any recent logs.
4. To check if Docker is functioning properly, you can list the Docker images on your system:

![image](https://github.com/neelay-16/DevOps---Configure-Docker/assets/135517502/3585430b-2d82-4308-a10a-09b939531c76)

If Docker is correctly installed, this command will list any available Docker images on your system.
5. To get detailed information about your Docker installation, including configuration details and resource usage, you can use the following command:

![image](https://github.com/neelay-16/DevOps---Configure-Docker/assets/135517502/0c9b4862-9a9e-4677-9771-64f4b8557a9e)

This command provides extensive information about your Docker setup.

6. You can also check it by pulling any image from the docker hub community which you mentioned in the local.repo file

![WhatsApp Image 2023-08-23 at 2 16 03 AM](https://github.com/neelay-16/DevOps---Configure-Docker/assets/135517502/59cd9335-f156-444e-a5cc-c26e1ca0c4fb)

![WhatsApp Image 2023-08-23 at 2 17 20 AM](https://github.com/neelay-16/DevOps---Configure-Docker/assets/135517502/e43f8c05-a378-427c-88fd-bf5594f21e6d)


By using one or more of these methods, you can ensure that Docker is properly installed and functioning on your Linux system. If you encounter any issues during installation or while running Docker commands, consult the Docker documentation or seek assistance from your system administrator or the Docker community for troubleshooting and support.
Or you can also reach out to me at neelayambalkar@gmail.com




