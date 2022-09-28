# How to Use
How to use/add to this resource
## Git/Github
### Setting up Git
1.  Go to [https://sourceforge.net/projects/git-osx-installer/files/git-2.33.0-intel-universal-mavericks.dmg/download?use_mirror=autoselect](https://sourceforge.net/projects/git-osx-installer/files/git-2.33.0-intel-universal-mavericks.dmg/download?use_mirror=autoselect) 
2.  The download should automatically start
3.  Run these two commands in your terminal, adding your name and email where needed.
4.  `git config --global user.name "John Doe"`
5. ` git config --global user.email johndoe@example.co`

With that, you should have git fully set up. 

### Setting up a GitHub account
1.  Go here and make an account: [https://github.com/join](https://github.com/join) 
2.  That's it.

Watch this video for an excellent example of how to use git & GitHub.
[https://www.youtube.com/watch?v=DVRQoVRzMIY](https://www.youtube.com/watch?v=DVRQoVRzMIY)

### Clone the Repository
1. Go to [this repository on github](https://github.com/201-991-Broncobotics/broncobotics-knowledge)
2. Click the green "code" button and copy the url
3. Run these commands in the directory you want to have the code in
	1. To change the working directory use the `cd` command. Ex:
		- `cd desktop`
4. `git clone https://github.com/201-991-Broncobotics/broncobotics-knowledge.git`
	- (this is the url you copied)
5.` git checkout main`

You should be ready to edit the code in it

## [Obsidian](https://obsidian.md/)
A markdown editor to edit files and upload the

1. Install it on your computer
2. Open the docs folder of the code that you cloned as a vault
3. Go to Settings -> Community Plugins -> Community Plugins/Browse
4. Search for Obsidian Git -> Install it
5. Scroll to the bottom of the community plugins tag and enable it
6. Make changes on the files
7. Push your changes and it should work
