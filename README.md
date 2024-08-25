## Hi there 👋

## NodeJS Wiki install  

### Download the binaries
VERSION=v18.17.1   
DISTRO=linux-x64   
wget https://nodejs.org/dist/$VERSION/node-$VERSION-$DISTRO.tar.xz   

### Decompress   
mkdir -p  /usr/local/lib/nodejs/
sudo tar -xvf node-$VERSION-$DISTRO.tar.xz -C /usr/local/lib/nodejs/   

### Edit the bashrc or zshrc   
VERSION=v18.17.1   
DISTRO=linux-x64   
export PATH=/usr/local/lib/nodejs/node-$VERSION-$DISTRO/bin:$PATH   

### Reload
source ~/.bashrc  
source ~/.zshrc

**r00t-64/r00t-64** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

