# TODOs
- create logo
- get screenshots
    - cover
    - Syntax highlighting in the Post/Page HTML editor
    - Settings Panel
    - Syntax highlighting in the Theme/Plugin editor
- push to `dev` then to `master`
- close this branch
- make `release` branch
    - add all released to that branch and tag them


## Testing
- general bugs
    - none currently
- browsers
    - Safari - seems ok
    - FireFox (Mac) - seems ok
    - Chrome (Mac) - seems ok
    - FireFox (Win10) - seems ok
    - Chrome (Win10) - seems ok
    - Edge - seems ok
    - IE 11 - seems ok
 

## TODO later:
- add all these as enhancement requests
- store scroll position as well as cursor position
- support `<!--nextpage-->` in shortcode parser
- add fullscreen to plugin/theme editor
- success/progress/failure ui for saving options
- [autoformat](http://codemirror.net/2/lib/util/formatting.js)? [demo](http://codemirror.net/2/demo/formatting.html) - this was discontinued
- addon/advanced options
	- keymaps
	- editor options:
		- style active line
		- matchBrackets
		- highlight selection matches
		- search
		- foldcode
	- code commands
		- commenting: Ctrl+/, Cmd+/
		- autoclose tags
		- autoclose brackets
		- [emmet](https://github.com/emmetio/codemirror)?
		- [spellcheck](https://github.com/NextStepWebs/codemirror-spell-checker)?
	- prevent reformatting like:
		- auto p
		- link to other auto p disabling plugins
- rtl support
- translation support
- IE & Edge Bug: adding content with the buttons doesn't work :(
	- ...because setting selection on a textarea doesn't work unless the text area is in focus
	- possible solution: 
		- detect mousedown on a button in the bar
		- give the real textarea focus and the proper selection
		- when that textarea changes, update the value in codemirror
		- then switch back to codemirror in the correct cursor position
- CodeMirror themes inspired by WordPress themes
	- and an auto theme that will match the CM theme to the WP theme - set by default
- compatible with other plugin:
	- [Site Origin Editor](https://siteorigin.com/widgets-bundle/)
	- [Advanced Custom Fields](https://www.advancedcustomfields.com/)
	- [Visual Composer](https://vc.wpbakery.com/)
	- [King Composer](https://wordpress.org/plugins/kingcomposer/)
	- [Revisionary](https://wordpress.org/plugins/revisionary/)
- read [bugs](https://wordpress.org/support/plugin/html-editor-syntax-highlighter) and add more TODOs


## links
- process user settings
	- [working with user metadata](https://developer.wordpress.org/plugins/users/working-with-user-metadata/)
	- [update_user_meta()](https://codex.wordpress.org/Function_Reference/update_user_meta)
- AJAX forms
	- [submitting a form in wordpress using ajax](https://teamtreehouse.com/community/submitting-a-form-in-wordpress-using-ajax)
	- [how to handle form submission](http://wordpress.stackexchange.com/questions/60758/how-to-handle-form-submission)
- [wp usage stats](https://wordpress.org/about/stats/)