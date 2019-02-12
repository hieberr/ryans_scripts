# ryans_scripts
Various useful scripts and things.


# [ryans_custom_prompt.bash](https://github.com/hieberr/ryans_scripts/blob/master/ryans_custom_prompt.bash)
My custom prompt which prints the current working directory as well as some git info if in a repository. 

To enable run the script from your ~/.bash_profile. 
For example, I have the file in ~/repos/util/ryans_scripts/ so in my .bash_profile
```
if [ -f ~/repos/util/ryans_scripts/ryans_custom_prompt.bash ]; then
  . ~/repos/util/ryans_scripts/ryans_custom_prompt.bash
fi
```
