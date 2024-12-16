# ci-cd-docker-azure
Pipeline CI/CD avec Docker et Azure

#Create a virtuel envirment for your running python app:
sudo apt update
sudo apt install python3-venv
python3 -m venv venv 
source venv/bin/activate

#Install flask in your virtuel python envirment:
pip install -r requirements

#Test application
python app.py

#Important !! : you must activate your project envirmnt every time you work with it : 
source venv/bin/avtivate

#Desactivate envirment :
deactivate

