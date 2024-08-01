# Neovim-configuration

This is my repository for storing my neovim configurations.

This configuration started from kickstart neovim. I separated the configurations into their own files for organization porpuses.
Feel free to yank anything from the configuration. The init_old.lua is pretty much the same that the init.lua from the kickstart neovim. Just with some comments erased.

the file _init.lua_ has the dependencies, in this case is the folder in witch my configs ar stored, that is _lua/covolan_.
Inside it, there is another _init.lua_ that points to the initialization of the settup (_set.lua_), the keybinds (_keymap.lua_) and the lazy file (_lazy_init.lua_).
This refers the lazy folder that has all the pluggins from lazy.
