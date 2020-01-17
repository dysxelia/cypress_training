# cypress_training
# Cypress LL training

### Prerequisite:
* Linux native environment or WSL if running on Windows
    <pre><code>Check "Setup WSL" guide in confluence</code></pre>

### Requirements:
1. Node.js
2. yarn
3. git
4. Visual Studio Code: https://code.visualstudio.com/


## Install node.js in WSL / Linux:
We are going to use nvm, which is a version manager for node, makes it easier to mantain the node version.
1) Instal nvm, with: 
<code>curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.2/install.sh | bash</code>
2) To verify installation, enter <code>command -v nvm</code> ...this should return <code>'nvm'</code>, if you receive <code>'command not found'</code> or no response at all, close your current terminal, reopen it, and try again.
3) Install latest v10 version of Node.js (recommended for NGA): <code>nvm install 10</code>
4) Verify that Node.js is installed and the currently default version with: <code>node --version</code>. Then verify that you have npm as well, with: <code>npm --version</code>

## Install yarn in WSL / Linux
1) Add the repository to your installation:
    <pre>
    <code>curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -</code></pre>
    <pre>
    <code>echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list</code></pre>
2) Update and install yarn
<pre><code>sudo apt update && sudo apt install --no-install-recommends yarn</code></pre>

## Install GIT in WSL / Linux
1) Start by updating the package index:
<code>sudo apt update</code>
2) Run the following command to install Git:
<code>sudo apt install git</code>
3) Verify the installation by typing the following command which will print the Git version:
<code>git --version</code>

That's it, you have successfully installed Git on your Ubuntu and you can start using it.


# Download and use this repo AFTER all of the above is installed
1) Create a 'repos' folder wherever is convinient for you (I recommend having it somwhere like .../Documents/repos)
2) Open a new terminal / WSL instance and navigate to that folder
3) Run the following command: 
    <pre><code>git clone https://github.com/OjelaNape/cypress_training.git</code></pre>
That's it, open Visual Studio Code, go to Files -> Open folder -> Search and open "cypress_training" folder
