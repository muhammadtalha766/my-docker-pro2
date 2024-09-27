git pull origin main
sudo docker-compose -f iac-docker-compose-file.yml down
sudo docker-compose -f iac-docker-compose-file.yml up --build -d

above 3 commands use in jenkins shell script to run all process
