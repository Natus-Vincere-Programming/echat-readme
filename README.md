# Site launch (Windows)
**Before starting, be sure to enable the backend part**
video demonstration https://drive.google.com/file/d/1o_E_NC0rX9IKaBg-kV3-gQMARe8DbpqS/view?usp=sharing
1. Download Node.js [from the link](https://nodejs.org/en)
2. Run the command in the terminal `npm install -g angular-http-server`
3. Download `eChat-application` [from the link](https://github.com/Natus-Vincere-Programming/eChat-application/releases) (he version of the site and the backend must match!!!)
4. Unpack and follow this path (where index.html is located)  <img width="900" alt="image1" src="https://github.com/user-attachments/assets/f1fdd8e3-3bf8-49e1-aef7-876ec89c95b4">
5. Enter `cmd` in the path and press Enter <img width="900" alt="image2" src="https://github.com/user-attachments/assets/dd2443ce-268f-478b-ab58-89703528eafd">
6. If the previous point does not work, then enter the path using  `cd folder`
7. A terminal will open with the path to index.html  ![image](https://github.com/user-attachments/assets/91b4a04e-4008-41f3-84b9-f90c317986c7)
8. In the same terminal, write the command `angular-http-server -p 4200`
9. The site is available [at the link](http://localhost:4200) (localhost:4200)
**Installing the backend**
1. Install [Docker Desktop](https://www.docker.com/products/docker-desktop/) and run it
2. Download the docker-compose.yml file from this repository
3. In the terminal, in the path where docker-compose.yml is located, write the *docker compose up* command
4. If everything is green, then everything is ok, and you can run the frontend part!![image](https://github.com/user-attachments/assets/9be9d477-70fa-459f-98e1-303aab6ea36d)

