# Nagad_Version_4
 
# sudo apt install iproute2 && sudo apt install wget && sudo apt install unzip && apt install nvtop

# sudo apt update && sudo apt upgrade

# apt-get update && apt-get install libgl1

# pip install fastapi uvicorn pydantic

# pip install pytz

# apt install nvtop

### https://nagad-pulse.sgp1.digitaloceanspaces.com/nagad_final_project.zip


wget "https://nagad-pulse.sgp1.digitaloceanspaces.com/nagad_final_project_version3.zip"
version 4 : wget "https://nagad-pulse.sgp1.digitaloceanspaces.com/nagad_final_project_version4.zip"

#  curl -s https://ngrok-agent.s3.amazonaws.com/ngrok.asc | sudo tee /etc/apt/trusted.gpg.d/ngrok.asc >/dev/null && echo "deb https://ngrok-agent.s3.amazonaws.com buster main" | sudo tee /etc/apt/sources.list.d/ngrok.list && sudo apt update && sudo apt install ngrok

# ngrok config add-authtoken 2Qm8hS1zPhVXiLjEdlI4738tLzF_2QJwGJMK5oTbQD33QSVXS

### OLD : # ngrok http --domain=facedetection.ngrok.dev 8000 /// # ngrok http --domain=hawkeyes.ngrok.app 8020 /// # ngrok http --domain=nagadpulse.ngrok.app 4444

### NEW : # ngrok http --domain=hasb.nagadpulse.com 4444

# pip install -r requirements.txt


***	uvicorn nagad_main_API:app --reload --port 8000		***


rakib:
-------

auth: ngrok config add-authtoken 2Q8xOjna6gvwQRiMTZayN1uEgWy_6uRD8M1b6rZtYMz4yLzAw



api: ngrok http --domain=similarly-close-orca.ngrok-free.app 8020



himel:
--------------------------

auth : ngrok config add-authtoken 2TmkpvbMuZyWWCpWF3kkmiKKepl_3UmLn9nGJygR2sGe6Be42

api : ngrok http --domain=https://caribou-neat-firstly.ngrok-free.app 80


api : ngrok tunnel --label edge=edghts_2WvHdrcQq10h0qzlBwK9gItS7Xy http://localhost:8000