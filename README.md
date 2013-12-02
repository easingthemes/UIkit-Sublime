UIkit-Sublime
=============

UIkit CSS Class name completion, for Sublime text editor.

<a href="http://getuikit.com" target="_blank" title="UIkit framework">UIkit Framework</a>

<a href="http://www.sublimetext.com" target="_blank" title="Sublime Text editor">Sublime Text editor</a>

__________________________________________________________

<h2>Update</h2>

Changed to sublime-snippet from sublime-completion. Due to issue with Sublime 3.
Use it as usually.
You can still download <a href="http://easingthemes.com/uikit/UIkit-Class.zip" target="_blank" title="Sublime Text editor">previous release</a>, if you want.

<h2>INSTALL</h2>

1.Trough Package Control
 - Pref --> Package Control - Install Package: search UIkit.

OR

2.Download zip file, open Sublime Text

 - In main menu go to Preferences --> Browse Packages
 - Extract ziped file in Packages folder that you just opened

<h2>ACTIVATE</h2>

If you already didn't activate Sublime autocomplete, you need to do it now.
 - In main menu go to Preferences --> Settings-User
 - Add Auto complete selectors: <code>"auto_complete_selector": "source, text"</code>
<pre><code>{
  "auto_complete_selector": "source, text"
}</code></pre>

<h2>USE</h2>

 - Inside class apostrophes start typing <code>uk</code>.
 - Class names are sorted alphabetically (Sublime style)
   - First block are two parts words, eg. uk-active
   - Than 3-parts words, eg. uk-icon-github
   - etc.

Enjoy coding.
