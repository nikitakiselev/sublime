My Sublime Text 3 config

```
import urllib.request,os,hashlib; h = 'df21e130d211cfc94d9b0905775a7c0f' + '1e3d39e33b79698005270310898eea76'; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); by = urllib.request.urlopen( 'http://packagecontrol.io/' + pf.replace(' ', '%20')).read(); dh = hashlib.sha256(by).hexdigest(); print('Error validating download (got %s instead of %s), please try manual install' % (dh, h)) if dh != h else open(os.path.join( ipp, pf), 'wb' ).write(by)
```

Install Material Theme.

```
{
    "auto_complete": true,
    "auto_indent": true,
    "default_encoding": "UTF-8",
    "detect_indentation": true,
    "draw_indent_guides": true,
    "draw_white_space": true,
    "enable_tab_scrolling": false,
    "smart_indent": true,
    "tab_completion": true,
    "font_face": "Fira Code",
    "font_size": 13,
    "font_options": [ "gray_antialias" ], 
    "margin": 5,
    "line_padding_bottom": 5,
    "line_padding_top": 5,
    "translate_tabs_to_spaces": true
}
```
