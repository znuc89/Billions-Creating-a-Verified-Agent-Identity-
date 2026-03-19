# Billions-Creating-a-Verified-Agent-Identity-
Grab Extra 2000 Free Power Points by Creating a Verified Agent Identity

1. Login to your GitHub here: http://github.com

2. Go to: http://github.com/codespaces and use the Blank template.

3. Use this commands (Terminal):

3.1. Install NPM:
npm install

3.2. Install node:
nvm install 20
nvm use 20

3.3. Creating a Verified Agent Identity

gh repo clone BillionsNetwork/verified-agent-identity

npx clawhub@latest install verified-agent-identity

cd verified-agent-identity

node scripts/createNewEthereumIdentity.js

node scripts/manualLinkHumanToAgent.js --challenge '{"name": "Agent Name", "description": "Short description of the agent"}'

4. Copy the link you got from GitHub with the prefix https://wallet.billions.network... and paste it on another tab.

Ex: node manualLinkHumanToAgent.js --challenge '{"name": "DEVOT", "description": "DEVOT agent"}'
https://wallet.billions.network#request_uri=https://identity-dashboard.billions.network/shortener/2f5153c9...

5. Sign in with your Billions Account and verify.

6. Finish!

7. Check result: 
https://official.app/y_W_Q3Bxc1lN



