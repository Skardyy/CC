# Goals  
CC is going to be an gui app that lets you start processes or shell scripts, those process can be later be debugged / killed / reload..  
* it should be easy and quick to firstly configure
* should be easy and nice way to start apps
* should have a small executable and fast loading times for a quick startup
* should have a way to receive intents so cli suppport can be added

## TODO:  
```diff
- create a function to get the default shell
- create a function that start apps / commands and get their pid
- create a way to quickly setup shortcuts or .urls for a quick setup
- create a setting for start on startup
- create a way to signal the pid
- create a easy way to add new commands / apps for the config
```

## How  
the app will be builded using tauri + vue for good looking ui + a system language for handling the os related tasks
