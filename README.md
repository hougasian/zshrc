# .zshrc

macOS 10.15 Catalina introduced zsh as the new default shell. The MacBook Pro I had at that time didn't have zshell's native configuration file .zshrc, so i had to add from a [template file](https://github.com/ohmyzsh/ohmyzsh/blob/master/templates/zshrc.zsh-template).

After purchasing an [Apple Silicon](https://www.apple.com/newsroom/2020/06/apple-announces-mac-transition-to-apple-silicon/) MBA, i realized that the rc config file just isn't there 😔 (it's here 😜)

> UPDATE: New M1 MBP running macOS Monterey 12.2.1 no longer needs the template file above. Try just using the `curl` or `wget` below first. 

## wget/curl

```
curl -LJO https://raw.githubusercontent.com/hougasian/zshrc/main/.zshrc
```
```
wget --no-check-certificate --content-disposition https://raw.githubusercontent.com/hougasian/zshrc/main/.zshrc
```

## Additional resources

### zsh
- [Themes](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes)
- [Plugins](https://github.com/ohmyzsh/ohmyzsh/wiki/Plugins)
- [Prompt colors](https://en.wikipedia.org/wiki/ANSI_escape_code)
- [Prompt expansion](https://zsh.sourceforge.io/Doc/Release/Prompt-Expansion.html)

### Other
- [iTerm2](https://iterm2.com/)
- [Hyper](https://hyper.is/)&dagger;
- [Atom](https://atom.io/)&dagger;
 
&dagger; _At the time of writing this, I decided to not run intel-based apps via Rosetta on the new Apple Silicon. I will likely switch to Hyper, and back to atom, once these [Electron](https://www.electronjs.org/)-based apps are updated._
