dotfiles
========

Day to day tricks to help productivity.


bash plugins
------------

The .bash_plugins dir has a few organized shell definitions (aliases, functions) I commonly use.
To enable any extra bash definitions script when launching a shell

	for PLUGIN in ~/.bash_plugins/*; do
    	. $PLUGIN
	done

