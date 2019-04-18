# 🐱☸ kubemoji

Standardizing Kubernetes with emojis. ⭐ if you like. Thanks 👍 

**Best viewed with [Noto](https://github.com/googlefonts/noto-emoji) compatible device** (Shell, Chrome on Linux or Anrdoid) - see [why](#why-noto). 


# Current proposal

Current kubemoji is a story about cats 🐱 and cookies songs 🍪🎵.

## Cluster and pods

| Type       | Emoji (this device) | Noto font |
| :--------- | :-----------------: | :-------- |
| Cluster<br/>🌌 | A Kubernetes cluster 🌌, a world made of nodes 🏝|  <img src="https://noto-website-2.storage.googleapis.com/emoji/emoji_u1f30c.png" alt="drawing" width="20" height="20"/> | 
| Pod<br/>🐱 |  A pod 🐱 lives on nodes 🏝 and get skills from one or more containers 🐱(🧠), 🐱(🧠🧠...)  | <img src="https://noto-website-2.storage.googleapis.com/emoji/emoji_u1f431.png" alt="drawing" width="20" height="20"/>  |
| Container<br/>🧠 | Containers 🧠 may be docker, CRI-IO, or any container technology you think about. | <img src="https://noto-website-2.storage.googleapis.com/emoji/emoji_u1f9e0.png" alt="drawing" width="20" height="20"/> | 
| Node<br/>🏝 | Nodes 🏝 is the place 🐱 can play. | <img src="https://noto-website-2.storage.googleapis.com/emoji/emoji_u1f3dd.png" alt="drawing" width="20" height="20"/> |  


## Network 

| Type       | Emoji (this device) | Noto font |
| :--------- | :-----------------: | :-------- |
| Port<br/>👂 | Ports listen for songs. Apply on Pods, Nodes and Containers : 🐱(👂), 🏝(👂), 🧠(👂) | <img src="https://noto-website-2.storage.googleapis.com/emoji/emoji_u1f442.png" alt="drawing" width="20" height="20"/>
| tcp <br/>🎵 | tcp is a way to send songs to pods 🐱. Example : 🎵? --> 🐱(👂) | <img src="https://noto-website-2.storage.googleapis.com/emoji/emoji_u1f3b5.png" alt="drawing" width="20" height="20"/> | 
| http <br/> 🍪 | Cookie song is the most played song in a cluster 🌌 : 🍪🎵? --> 🐱(👂) | <img src="https://noto-website-2.storage.googleapis.com/emoji/emoji_u1f36a.png" alt="drawing" width="20" height="20"/> |    


# About [noto](https://github.com/googlefonts/noto-emoji) 

Currently known compatible devices : chrome on android, chrome on Linux, Linux shells.

Motivations : 
1. : noto is the only emoji font installed on Linux. It's working quite well in shell (debian, centos and ubuntu - bash and zsh) and since emojis can be quite confusing from on font to another, it's better to view this guide with a noto compatible device.

2. : monospace font and emojis are no good friends : alignement is a real nightmare. Take a look at the bellow sequence : if you see it aligned and not with a Noto font, please open an issue and tell me more cause I don't now alternative fonts that align \<pre/> blocks correctly. 
```
            🐱(👂)     🧠(👂)
            |          |
🍪🎵? ----> |          |
            | -------> |   
            | <--🍪🎵!-|
    <------ | 
```
