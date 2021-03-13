The config is complete but still WIP as Im new to lua and slowly learning vim stuffs , so I'll keep adding new features like snippets etc and clean the config!

# Screenshots

<img src ="https://raw.githubusercontent.com/siduck76/personal-backup/master/rice%20flex/initialNvim.png">
<img src ="https://raw.githubusercontent.com/siduck76/personal-backup/master/rice%20flex/nvimRice2.png">

# Some VERY COOL lua plugins I use 

- nvim-lspkind , for showing lil icons/pictograms on completion items
 <img src = "https://raw.githubusercontent.com/siduck76/personal-backup/master/rice%20flex/lspkind.png">
 
- nvim-tree.lua , a fast file tree 
 <img src = "https://raw.githubusercontent.com/siduck76/personal-backup/master/rice%20flex/nvimtree.png">
 
- telescope-nvim , a fuzzy file finder , picker , sorter , previewer and much more!
 <img src = "https://raw.githubusercontent.com/siduck76/personal-backup/master/rice%20flex/tel.png">
 <img src = "https://raw.githubusercontent.com/siduck76/personal-backup/master/rice%20flex/telmedia.png">


- galaxyline , a statusline plugin
 <img src = "https://raw.githubusercontent.com/siduck76/personal-backup/master/rice%20flex/statusline.png">
 
- gitsigns.nvim , to show git signs of a repo on the signcolumn to indicate diffs/changes etc  (needs plenary.nvim)

- nvim-bufferline.lua , as a top bufferline like thing which lets me handle tabs like switching , closing tabs.
 <img src = "https://raw.githubusercontent.com/siduck76/personal-backup/master/rice%20flex/bufferline.png">
 
- nvim-web-devicons , lua fork of vim devicons which lets me change icons of filetypes
 <img src = "https://raw.githubusercontent.com/siduck76/personal-backup/master/rice%20flex/image.png">
 
- nvim-treesitter , better syntax highlighting for programming languages ( my config just has html,css,js support for now ). 

 without Treesitter 
 <img src = "https://raw.githubusercontent.com/siduck76/personal-backup/master/rice%20flex/woTree.png">
 
 with Treesitter 
 <img src = "https://raw.githubusercontent.com/siduck76/personal-backup/master/rice%20flex/wiTree.png">


# Clone my setup

- Install neovim-nightly , also use a nerdfont on your terminal.
- Install packer.nvim 

` 
git clone https://github.com/wbthomason/packer.nvim\
 ~/.local/share/nvim/site/pack/packer/start/packer.nvim
 `
 
 - Open neovim and install all plugins , :PackerInstall and :TSUpdate 
 - Install language servers and prettier ( for autocompletion etc and code formatting , nodejs should be installed too!) 
 
 `  sudo npm install -g vscode-html-languageserver-bin typescript typescript-language-server  vscode-css-languageserver-bin prettier
 ` 
 
 
 
