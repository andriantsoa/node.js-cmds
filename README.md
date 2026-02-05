# node.js-cmds
Some interresting commands to manage node and npm


# get npm config with all default values
npm config ls -l

# get npm configs
npm config list

# set npm cache
npm config set cache D:\yourNodeJsFolder\node-repo\npm --global

# get npm cache status
npm --global cache verify

# clean node.js installation
- Delete “npm” folder from the following path C:UsersYourUserNameAppDataRoaming
- After deleting the npm folder, uninstall Node.js
- Reinstall Node.js (steps mentioned above)
- Install Angular Cli by running this command in CMD npm install -g @angular/cli@latest
- Now type “ng” or ng –version or ng -v in your terminal
- Confirmation that ng is working fine on your system now: Also if you type npm ls --global

# for npm cache custom manual conf, go to programFiles/nodejs/npmrc and set:
prefix=D:\dossier\node-repo\npm
cache=D:\dossier\node-repo\npm-cache

all globally installed package into these folders
