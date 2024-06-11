# nubit light node 

500 mb ram 40 gb ssd storage

Update VPS and Install Necessary Packages

sudo apt update && sudo apt upgrade -y

sudo apt install curl git wget build-essential jq screen -y

Create a Screen

screen -S nubit

Run the Script:

curl -sL1 https://nubit.sh | bash

 Save the MNEMONIC securely as it will only appear once. You can find the mnemonic.txt file in the nubit-node directory:
 
cat $HOME/nubit-node/mnemonic.txt
