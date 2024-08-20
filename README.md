# Rust completion for zsh

`rustup`, and `cargo`, completion for [zsh](http://www.zsh.org). 
The intention of this repo is to allow easy management of completions from `rustup completions` from a zsh plugin manager. 

## Installation
### Manually
Download the `src` folder somewhere you want to install, and add the following lines in your `.zshrc`.

```
export fpath=(path/to/rust-zsh-completions/src $fpath)
autoload -U compinit && compinit
```

### Using zplug
If you use [zplug](https://github.com/zplug/zplug), add the following line to your `.zshrc`.

```
zplug 'ShiromMakkad/rust-zsh-completions'
```


## License
[MIT](https://github.com/ShiromMakkad/rust-zsh-completions/blob/master/LICENSE)


## Author
[ShiromMakkad](https://github.com/ShiromMakkad) forked from [ryutok](https://github.com/ryutok)
