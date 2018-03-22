![image](https://raw.githubusercontent.com/alexanderjeurissen/ombre.zsh/master/assets/ombre_logo.png)

> Some little splinter
> Of shadow purls
> And weals down
> The slewed stone
> Chapel steps,
> Slinks along
> The riverrock wall
> And disappears
> Into the light.
> ~ Poem by James Galvin

A light Black & White ZSH prompt that favors simplicity and minimalism.
Looks even more awesome when combined with [Sombre.tmux](https://github.com/alexanderjeurissen/sombre.tmux)

![image](https://raw.githubusercontent.com/alexanderjeurissen/ombre.zsh/master/assets/commiting.png)

## Additional Screenshots
### Rebasing
![image](https://raw.githubusercontent.com/alexanderjeurissen/ombre.zsh/master/assets/interactive_rebase.png)

### Solving a merge conflict
![image](https://raw.githubusercontent.com/alexanderjeurissen/ombre.zsh/master/assets/merging.png)

### Magic enter (pressing enter with empty command line)
![image](https://raw.githubusercontent.com/alexanderjeurissen/ombre.zsh/master/assets/magic_enter.png)

## Installation
I personally use [zplug](https://github.com/zplug/zplug) as my zsh plugin manager of choice.
That being said, ombre.zsh should be compatible with most zsh plugin managers.

### Option 1: Install for Vanilla ZSH

If you just use a vanilla ZSH install, simply clone this repository and
reference it in your `~/.zshrc`:

    $ git clone https://github.com/alexanderjeurissen/ombre.zsh.git ~/ombre.zsh
    $ echo 'source  ~/ombre.zsh/prompt_ombre_setup' >> ~/.zshrc

### Option 2: Install for Oh-My-ZSH

To install this theme for use in
[Oh-My-Zsh](https://github.com/robbyrussell/oh-my-zsh), clone this repository
into your OMZ `custom/themes` directory.

    $ git clone https://github.com/alexanderjeurissen/ombre.zsh.git ~/.oh-my-zsh/custom/themes/ombre.zsh

You then need to select this theme in your `~/.zshrc`:

    ZSH_THEME="ombre.zsh/prompt_ombre_setup"

### Option 3: Install for Prezto

To install this theme for use in Prezto, clone this repository into your
[Prezto](https://github.com/sorin-ionescu/prezto) `prompt/external` directory.

    $ git clone https://github.com/alexanderjeurissen/ombre.zsh.git  ~/.zprezto/modules/prompt/external/ombre.zsh
    $ ln -s ~/.zprezto/modules/prompt/external/ombre.zsh/prompt_ombre_setup ~/.zprezto/modules/prompt/functions/prompt_ombre_setup

You then need to select this theme in your `~/.zpreztorc`:

    zstyle ':prezto:module:prompt' theme 'ombre'

### Option 4: Install for antigen

To install this theme for use in [antigen](https://github.com/zsh-users/antigen), just add this at the beginning
of your `~/.zshrc`:

    antigen theme alexanderjeurissen/ombre.zsh ombre
    antigen apply

You may need to do a `rm -rf ~/.antigen` to force a reinstall of all the antigen bundles. Also, remember to restart your terminal emulator after this step.

### Option 5: Install for Zplug

To install this theme for use in [Zplug](https://github.com/zplug/zplug), just add this
in your `~/.zshrc`:

    zplug "alexanderjeurissen/ombre.zsh", use:prompt_ombre_setup

### Option 6: Install for Zgen

To install this theme for use in [zgen](https://github.com/tarjoilija/zgen), just add this
in your `~/.zshrc`:

    zgen load alexanderjeurissen/ombre.zsh ombre

### Option 7: Install for Antibody

To install this theme for use in [Antibody](https://github.com/caarlos0/antibody), just add this
in your `~/.zshrc`:

    antibody bundle alexanderjeurissen/ombre.zsh

### Option 8: Install for ZPM

To install this theme for use in [ZPM](https://github.com/horosgrisa/ZPM), just add this
in your `~/.zshrc`:

    Plug alexanderjeurissen/ombre.zsh
    source ~/.local/share/zpm/plugins/ombre.zsh/prompt_ombre_setup

### Option 9: Install for ZIM

To install this theme for use in ZIM, clone this repository into your
[ZIM](https://github.com/Eriner/zim) `prompt/external-themes` directory.

    $ git clone https://github.com/alexanderjeurissen/ombre.zsh.git ~/.zim/modules/prompt/external-themes/ombre.zsh
    $ ln -s ~/.zim/modules/prompt/external-themes/ombre.zsh/prompt_ombre_setup ~/.zim/modules/prompt/functions/prompt_ombre_setup

You need to select this theme in your `~/.zimrc`:

    zprompt_theme='ombre'

