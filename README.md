<p align="center">
    <img src="https://user-images.githubusercontent.com/30529572/60157440-60a58300-980c-11e9-8ec6-020be154b566.gif" width= "150px">
</p>
<h1 align="center">Dev Environment Config</h1>

>When somebody begins a sentence with “IT WOULD BE NICE IF..” the right thing to do is to wait politely for the speaker to finish. No project ever gets around to the it-would-be-nice features: or if they do, they regret it. Wait for sentences that begin “WE HAVE TO..” and pay close attention, and see if you agree. **- Tom Van Vleck**
 
> Are you a programmer? Do you wanna spend more time thinking and solving problems rather than writing biolerplate code again and again? Are you sick of bad navigation? Well this is the solution for you!


<br/>


### Dev environment tools

- [X] `zsh` shell + plugins
- [X] `terminator` tiling manager
- [X] `vim` editor + plugins
- [X] `ranger` file manager

<br/>

### References

* [Oh my zsh](https://github.com/robbyrussell/oh-my-zsh.git)
* [terminator config](https://www.systutorials.com/docs/linux/man/5-terminator_config/)
* [zsh plugins](https://github.com/robbyrussell/oh-my-zsh/wiki/Plugins)
* [shell themes](https://github.com/robbyrussell/oh-my-zsh/wiki/Themes)

<br/>


![image](https://user-images.githubusercontent.com/30529572/60173214-dd942500-982b-11e9-8741-e867f2bbce70.png)

<br/>

### Vim plugins included

* [vim-go](https://github.com/fatih/vim-go.git)
* [ctrlp.vim](https://github.com/kien/ctrlp.vim.git)
* [airline](https://github.com/vim-airline/vim-airline.git)
* [emmet-vim](https://github.com/mattn/emmet-vim.git)
* [vim-fugitive](https://github.com/tpope/vim-fugitive.git)
* [nerdtree](https://github.com/scrooloose/nerdtree.git)
* [vim-multiple-cursors](https://github.com/terryma/vim-multiple-cursors.git)
* [YouCompleteMe](https://github.com/ycm-core/YouCompleteMe.git)
* [vim-yaml](https://github.com/stephpy/vim-yaml.git)
* [lightline.vim](https://github.com/itchyny/lightline.vim.git)
* [pathogen](https://github.com/tpope/vim-pathogen.git)

<br/>

### Zsh plugins included 

* git
* [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions)

<br/>

### Recommended keyboard shortcuts for terminator 

* `Alt`+`h`: Move to the left tile
* `Alt`+`j`: Move to the tile below
* `Alt`+`k`: Move to the tile above
* `Alt`+`l`: Move to the right tile
* `Alt`+`1`: Shift to tab 1
* `Alt`+`2`: Shift to tab 2
* `Ctrl`+`Shift`+`o`: Create new vertical tile
* `Ctrl`+`Shift`+`e`: Create new horizontal tile
* `Ctrl`+`Shift`+`d`: Open terminator in custom mode

<br/>

### Optional monitoring tools

* [gotop](https://github.com/cjbassi/gotop.git)
* [htop](https://github.com/hishamhm/htop.git)
* [nvtop](https://github.com/Syllo/nvtop.git)

<br/>

![image](https://user-images.githubusercontent.com/30529572/60172993-71b1bc80-982b-11e9-8adb-367095bbd959.png)

<br/>

### Getting started
Follow the following steps for instantly getting started

```bash
# Clone the repo in you $HOME
$ git clone https://github.com/L04DB4L4NC3R/DEC.git

# cd into the directory
$ cd DEC

# Run bootstrap and setup, and you are good to go
$ make bootstrap
$ make setup

# To install tools (optional)
# Make sure you have graphics drivers installed
$ make tools
```

<br/>

### Contributing
If you want to add a `vim` plugin, make sure it uses pathogen. Just append the link to its repo [here](https://github.com/L04DB4L4NC3R/DEC/blob/master/vim-plugins).

Make sure you run `make bootstrap && make setup` for the changes to apply

<br/>

Made with :heart: by Angad Sharma
