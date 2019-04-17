# 🐱☸ kubemoji

Standardizing Kubernetes with emojis. ⭐ if you like. Thanks 👍 

**Best viewed with [Noto](https://github.com/googlefonts/noto-emoji) compatible device** (Shell, Chrome on Linux or Anrdoid) - see [why](#why-noto). 


# Current reference

Current kubemoji is a story about cats 🐱 and cookies songs 🍪🎵.

## Cluster and pods

| Type       | Emoji (this device) | Noto font | Comment     |
| :------------- | :----------: | :----------: | -----------: |
| Cluster | 🌌 | <img src="https://noto-website-2.storage.googleapis.com/emoji/emoji_u1f30c.png" alt="drawing" width="20" height="20"/> | A Kubernetes cluster is made of nodes 🏝
| Pod | 🐱 |   <img src="https://noto-website-2.storage.googleapis.com/emoji/emoji_u1f431.png" alt="drawing" width="20" height="20"/>  | A pod 🐱 lives on nodes 🏝 and get skills from one or more containers 🐱(🧠), 🐱(🧠🧠...)  
| Container | 🧠 | <img src="https://noto-website-2.storage.googleapis.com/emoji/emoji_u1f9e0.png" alt="drawing" width="20" height="20"/> | Containers 🧠 may be docker, CRI-IO, or any container technology you think about. 
| Node | 🏝 | <img src="https://noto-website-2.storage.googleapis.com/emoji/emoji_u1f3dd.png" alt="drawing" width="20" height="20"/> | Nodes 🏝 is the place 🐱 can play. Also known as "worker" or "minion" (deprecatedà). 


## Network 

| Type       | Emoji (this device) | Noto font | Comment     |
| :------------- | :----------: | :----------: | :---------- |
| Port | 👂 |  <img src="https://noto-website-2.storage.googleapis.com/emoji/emoji_u1f442.png" alt="drawing" width="20" height="20"/>| Ports listen for songs. Apply on Pods, Nodes and Containers : 🐱(👂), 🏝(👂), 🧠(👂)
| tcp | 🎵 | <img src="https://noto-website-2.storage.googleapis.com/emoji/emoji_u1f3b5.png" alt="drawing" width="20" height="20"/> | tcp is a way to send songs to pods 🐱. Example : 🎵? --> 🐱(👂)
| http | 🍪 | <img src="https://noto-website-2.storage.googleapis.com/emoji/emoji_u1f36a.png" alt="drawing" width="20" height="20"/> | Cookie song is the most played song in a cluster 🌌 : 🍪🎵? --> 🐱(👂)   

# Why noto

1st : Noto is the only emoji font installed in Linux. It's working quite well in shell and  emojis can be quite confusing from on font to another. It's better to view the refence guide with a Noto compatible device.

2nd : monospace font and emojis are no good friends, alignement is a real nightmare. Take a look at the bellow sequence : if you see it aligned and not with a Noto font, please open an issue and tell me more cause I don't now alternative fonts that align \<pre/> blocks correctly. 
```
            🐱(👂)     🧠(👂)
            |          |
🍪🎵? ----> |          |
            | -------> |   
            | <--🍪🎵!-|
    <------ | 
```
