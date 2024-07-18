<div align=center>
  <img src="https://github.com/TempGROX/TempGROX/blob/main/src/photos/ayyW6i94_200x200.jpg">

  <h1 align=center>Initia-Install-Node-Guide</h1>
  Here is the instruction for launching the Initia project node
</div>
<br>

# Testnet Information

|KEY|VALUE|
|:--|:----|
|Chain-ID|initiation-1|
|actual initia Version|v0.2.15|
|Genesis file|https://initia.s3.ap-southeast-1.amazonaws.com/initiation-1/genesis.json|
|Known Peers|093e1b89a498b6a8760ad2188fbda30a05e4f300@35.240.207.217:26656,2c729d33d22d8cdae6658bed97b3097241ca586c@195.14.6.129:26019|
|Known Seed|2eaa272622d1ba6796100ab39f58c75d458b9dbc@34.142.181.82:26656,c28827cb96c14c905b127b92065a3fb4cd77d7f6@testnet-seeds.whispernode.com:25756|
|Address Book|https://initia.s3.ap-southeast-1.amazonaws.com/initiation-1/addrbook.json|

# Clone the initia repository
Now we just need to clone the repository to our computer and select the current branch. See the current version of the branch above.

```bash
git clone https://github.com/initia-labs/initia
cd initia

git checkout [version]
```

# Build initia
Now we are building a project.

```bash
make install
```

# Confirmation
In order to make sure that the previous steps are correct, we can try to output the full version of initia.

```bash
initiad version --long
```

# Configuration
After we have fully installed initia and made sure of this, we should make a basic configuration of the node!

```bash
# init initiad with default setting
initiad init local --chain-id testnet

# modify node section to the remote full node rpc address.
vim ~/.initia/config/client.toml
```

# Add keys
Now we can create the keys ourselves. This is done with the following command:

```bash
initiad keys add <your-key-name>
```

# The end!
If you liked this guide, please go to all my social networks)

<br>
<div id="badges" align="center">
  <a href="https://discord.com/users/961408999411048461">
    <img src="https://img.shields.io/badge/Discord-blue?style=for-the-badge&logo=https%3A%2F%2Fimg.icons8.com%2Fios%2F50%2Fmedium-logo.png&logoColor=white" alt="LinkedIn Badge"/>
  </a>
  <a href="https://medium.com/@James_Brandon">
    <img src="https://img.shields.io/badge/Medium-black?style=for-the-badge&logo=https%3A%2F%2Fimg.icons8.com%2Fios%2F50%2Fmedium-logo.png&logoColor=white" alt="Youtube Badge"/>
  </a>
  <a href="https://keybase.io/jamesbrandon">
    <img src="https://img.shields.io/badge/Keybase-orange?style=for-the-badge&logo=https%3A%2F%2Fimg.icons8.com%2Fios%2F50%2Fmedium-logo.png&logoColor=white">
  </a>
  <a href="https://x.com/JBTGrox">
    <img src="https://img.shields.io/badge/Twitter-blue?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter Badge"/>
  </a>
  <a href="https://linktr.ee/JBrandon_?utm_source=linktree_admin_share">
    <img src="https://img.shields.io/badge/Linktree-green?style=for-the-badge&logo=https%3A%2F%2Fimg.icons8.com%2Fios%2F50%2Fmedium-logo.png&logoColor=white">
  </a>
</div>
