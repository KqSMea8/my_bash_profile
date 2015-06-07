# my_bash_profile
	a bash profile that include serval convenient command
# usage
1. check out this git on ~/.my_bash_profile:
```shell
	git clone https://github.com/wisonlin/my_bash_profile.git ~/.my_bash_profile
```
2. add the following code into your ~/.bash_profile
```shell
	if [ -f ~/.my_bash_profile/.bash_profile_config ]; then
		source ~/.my_bash_profile/.bash_profile_config
	fi
```
3. execute the following command in your shell
```shell
	source ~/.bash_profile
```
