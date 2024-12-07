# Doom_Docker_Deployment
Welcome to DOCKER-DOOM, your gateway to experiencing the classic game DOOM right from your browser within a Docker.
This project demonstrates the deployment of Doom using Docker, showcasing the seamless integration of containerization.

"Doom" is the legendary first-person shooter video game developed by id Software, first released in 1993. It is widely regarded as one of the most influential titles in video game history, pioneering immersive 3D graphics, networked multiplayer gaming, and modding culture. The "Video of Doom" in this project serves as a tribute to this iconic game, featuring content inspired by its rich history, gameplay mechanics, and cultural impact.

## Stand-alone Deployment
Environment Variables APP_ARGS - Additional arguments to pass to the application when launched. Stand-alone Deployment. This image was designed to run natively within Kasm Workspaces, but it can also be deployed stand-alone and accessed through a web browser.
This image can be deployed stand-alone and accessed through a web browser.

sudo docker run --rm -it --shm-size=512m -p 6901:6901 -e VNC_PW=password kasmweb/doom:1.16.0

The container is now accessible via a browser : https://IP_OF_SERVER:6901


User : kasm_user

Password: password

Please note that some functionality, such as audio, uploads, downloads, and microphone pass-through, is only available when using Kasm Workspaces for orchestration.

## Video PREVIEW



https://github.com/user-attachments/assets/3e49dc96-84ca-4fec-8839-935085bf5566




