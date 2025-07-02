Create New Codespace
then do 
Sudo apt update
Sudo apt upgrade
adhen run 
java -Xmx8G -Xms4G -jar paper.jar --nogui

then open new terminal and run
ngrok config add-authtoken
ngrok tcp 25565

after u finish the server turn it off by going to all the terminals that are running and ctrl +c several times 
then save the world by
git add .
git commit -m "saving data"
git push
