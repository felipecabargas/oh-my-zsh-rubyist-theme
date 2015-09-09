#Rubyist theme for oh-my-zsh

**Description**
---

The shell shows the following info:

	host § folder rvm:(ruby-version) nvm:(node-version) git:(branch) git-status

Example:

![](theme.png)

The *purist* version doesn't show nvm info:

	host § folder rvm:(ruby-version) git:(branch) git-status

**Instalation**
---

1. Clone this repository
2. Move theme file to your Oh-My-Zsh instalation themes folder:

		mv path/to/rubyist.zsh-theme ~/.oh-my-zsh/themes/

or:

		mv path/to/pure-rubyist.zsh-theme ~/.oh-my-zsh/themes/rubyist.zsh-theme

3. Edit the `ZSH_THEME` var in your `.zshrc` file in order to match the theme:

		ZSH_THEME = "rubyist"

4. Set your hostname:

		sudo scutil --set HostName new-hostname

5. Enjoy!

---

**Felipe Cabargas 2014** &copy; Published under license [CC BY-ND 2.0](http://creativecommons.org/licenses/by-nd/2.0/)