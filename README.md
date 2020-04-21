Example plugin for xxh bash shell. It just prints hello message on loading. 

## Create your bash xxh plugin
1. Fork this repo
2. Edit the plugin files:
    * `pluginrc.sh` -  this script will be executed on the host when you connect to the host. Put here your functions, environment variables, aliases and whatever you need.
    * `build.sh` - this script should be executed to prepare the plugin on local xxh. It will be executed automatically if `build` directory is not exists.
3. Replace this list to description of your xxh plugin (review other xxh plugins)
4. Push your commits and rename your repo to `xxh-plugin-bash-yourtitle`
5. Install the plugin to your xxh home:
```
xxh +I xxh-plugin-bash-yourtitle+git+https://github.com/yourname/xxh-plugin-bash-yourtitle
```
6. Try connect in update mode: `xxh [user@]host[:port] +s bash +if`

## Examples

🔎 [Search xxh plugins on Github](https://github.com/search?q=xxh-plugin-bash&type=Repositories) or [Bitbucket](https://bitbucket.org/repo/all?name=xxh-plugin-bash)


## Install
From xxh repo:
```
xxh +I xxh-plugin-bash-example
```
From any repo:
```
xxh +I xxh-plugin-bash-example+git+https://github.com/xxh/xxh-plugin-bash-example
```    
Connect:
``````
xxh yourhost +s bash +if
```
