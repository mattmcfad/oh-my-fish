# Install

## copy template of fish config into your config
* `cp ~/.oh-my-fish/templates/config.fish ~/.config/`

* [install rvm:](https://rvm.io/rvm/install)

* [install powerline:](https://powerline.readthedocs.org/en/master/installation/osx.html)

* [install fonts:](https://github.com/powerline/fonts)

* Set font in iTerm2 to a downloaded powerline font


- ### install nvm
    - touch ~/.bash_profile
    - curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.2/install.sh | bash
    - cd ~/.config/fish
    - git clone git://github.com/passcod/nvm-fish-wrapper.git nvm-wrapper
    - nvm install v6
    - nvm install v7
    - nvm install v8