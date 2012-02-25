# My Sublime Text 2 packages

####+ settings, snippets and other goodies.

---
#  

- Clone to `~/Library/Application Support/Sublime Text 2`  

- Using [Meslo font](https://github.com/andreberg/Meslo-Font).  
	Install from `/User/Meslo LG DZ v1.0.zip` (or change in settings – `User/Preferences.sublime-settings` – to use another font)  

- Also using my own icon: `/User/Sublime Text 2.icns`. Replace the one in `/Applications/Sublime Text 2.app/Contents/Resources` (or just run `User/Extras/Replace ST2 icon.app`)

- Change the default comment syntax in Haml from `//` to `-#` by editing line 17 in `Rails/Ruby Haml Comments.tmPreferences`.

##Files to ignore changes to but still keep in the repo: 

*(this command needs to be run on every machine where the repo is cloned)*

	git update-index --assume-unchanged User/Package\ Control.sublime-settings; git update-index --assume-unchanged SideBarEnhancements/package-metadata.json; git update-index --assume-unchanged SyncedSideBar/SyncedSideBar.py; git update-index --assume-unchanged SyncedSideBar/package-metadata.json; git update-index --assume-unchanged BracketHighlighter/BracketHighlighter.py; git update-index --assume-unchanged BracketHighlighter/package-metadata.json; git update-index --assume-unchanged BracketHighlighter/readme.md; git update-index --assume-unchanged Markdown\ Preview/README.md; git update-index --assume-unchanged Markdown\ Preview/package-metadata.json; git update-index --assume-unchanged SideBarEnhancements/readme.md; git update-index --assume-unchanged Theme\ -\ Soda/Soda\ Dark.sublime-theme; git update-index --assume-unchanged Theme\ -\ Soda/Soda\ Light.sublime-theme; git update-index --assume-unchanged Theme\ -\ Soda/package-metadata.json;