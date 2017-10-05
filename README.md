# Node-Install-Script

# To install the BPL Node using the script please follow these steps

git clone https://github.com/blockpool-io/Node-Install-Script.git

./BPL_Node_Install_Script.sh

After installing you will need to configure your config file.  

# Add configurations for your node

	Change the following in config.mainnet.json :
“address“: “set your IP”

“database”: “set database name”

“user”: “set database user”

“password”: “set database password”

# Update your secret

"forging": {
        
	"force": false,
       
       "secret": ["this is my secret"],
        
	"access": {
          
	  "whiteList": [
           
	   "127.0.0.1"
           
	   ]
       
       }
  
  },
