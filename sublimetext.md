#### Download
[link](http://www.sublimetext.com/)   

#### Package install
[install package](https://packagecontrol.io/installation)   

#### Packages
````html
⌘ ⇧ P => input "Package Control", Enter => input package name
````
*Emmet*    
*jQuery*    
*Sass*    
*Vintage Mode*    
*Code​Kit Commands*    
*Flatland*（主题）    
*Seti_UI*（主题）    
*SideBarEnhancements*    
*Nettuts + Fetch*    
*Alignment*    
````html
select ==> ⌃ ⌘ A    
````
*AdvancedNewFile*  
````html
(quickly create new files)        
⌥ ⌘ N ==> type file path    
````
*sublime Linter*  
````html
保存时会自动提示html，css等的语法错误，高亮显示    
````
*BracketHighlighter*   
````html
括弧高亮显示    
````
*Clipboard Manager*   
````html
剪切板历史，可以保存多个复制信息    
⌥ ⌘ V   
````

#### Sublime Text shourcuts
````html
Editing
⌘ ↩        Insert line after
⌘ ⇧ ↩        Insert line before
⌃ ⌘ ↑/↓        Move line/selection up / down

⌘ L        Select line - Repeat to select next lines
⌘ C        Copy current line (if no selection)
⌘ D        Select word - Repeat select others occurrences
⌘ ⇧ D        Duplicate line(s)
⌃ ⌘ G        Select all
⌘ ⇧ A       Expand selection to tag

⌃ M        Jump to matching brackets    Repeat to jump to opening brackets
⌃ ⇧ M        Select all contents of the current parentheses
⌃ ⇧ ↑/↓       Column selection up / down
⌃ ⌥ ↑/↓       Keyboard scrolling

⌘ X          Cut Line
⌃⇧K        Delete line
⌘ K, ⌘ K       Delete from cursor to end of line
⌘ ⌫        Delete from cursor to start of line
⌘ ⇧ ⌫        Delete from cursor to start of line (keep indent)

⌘ ]        Indent current line(s)
⌘ [        Un-indent current line(s)
⌘ J        Join line below to the end of the current line
⌘ K U          To upper case
⌘ K L           To lower case
⌘ /        Comment/un-comment current line
⌥ ⌘ /        Block comment current selection

⌘ Y        Redo, or repeat last keyboard shortcut command
⌘ ⇧ V        Paste and indent correctly
⌃ Space        Select next auto-complete suggestion
⌃ U        Soft undo; jumps to your last change before undoing change when repeated
⌃ ⇧ W        Wrap Selection in html tag

Navigation
⌘ R       Jump to symbol
⌘ P/T       Jump to files
⌃ G         Go to line
⌥ ⌘ ←/→       Switch file
⌃ ⌘ P           Switch project

General
⌘ ⇧ P        Command prompt
⌘ K, ⌘ B       Toggle side bar
⌃ ⇧ P        Show scope in status bar
⌘ N          New file
⌘ ⇧ N          New window

Find/Replace
⌘ F        Find
⌘ ⌥ F        Replace
⌘ ⇧ F        Find in files
⌥ ⌘ G          Next matching selection
⌥ ⌘ ⇧ G          Prev matching selection

Tabs
⌘ ⇧ t        Open last closed tab
^ Tab        Cycle up through tabs
⇧ ^ Tab        Cycle down through tabs

Split window
⌘ ⌥ 2        Split view into two columns
⌘ ⌥ 1        Revert view to single column
⌘ ⌥ 5        Set view to grid (4 groups)
⌃ [NUM]        Jump to group where num is 1-4
⌃ ⇧ [NUM]        Move file to specified group where num is 1-4

Bookmarks
⌘ F2       Toggle bookmark
F2       Next bookmark
⇧ F2       Previous bookmark
⇧ ⌘ F2       Clear bookmarks
````

#### Emmet shortcuts
[link](http://emmet.io/)    
````html
⌘ ⇧ , / .          Select Item (html / css)
⌘ ⇧ K          Select matching Tag
⌃ ⇧ T           Go to matching pair
⌃ ⌥ ←/→          Go to Edit Point

⌥ ⇧ /          Toggle Comment (html / css)
⌘ ⇧ '          Split/Join Tag

⌃ ⇧ I          Update image size (html / css)
⌃ ⇧ D          Encode/Decode Image to data:URL

⌘ ⇧ Y          Evaluate Math Expression
⌃ ↑/↓          Increment/Decrement Number by 1
⌥ ↑/↓          Increment/Decrement Number by 0.1
⌥ ⌘ ↑/↓          Increment/Decrement Number by 10

⌃ E          Expand Abbreviation
⌃ ⌥ Enter          Expand Abbreviation preview
⌃ W          Wrap with Abbreviation
⌘ ‘           Remove Tag

⌘ ⇧ R          Reflect CSS Value
lg(left, #fc0 30%, red)          Gradients
````

#### User Setting
````json
User：
{
     "auto_complete_commit_on_tab": true,
     "caret_extra_width": 2,
     "folder_exclude_patterns":
     [
          ".svn",
          ".git",
          ".hg",
          "CVS",
     ],
     "file_exclude_patterns":
     [
          "*.css.map",
          "*.scssc"
     ],
     "font_face": "Courier New",
     "font_size": 24,
     "highlight_line": true,
     "overlay_scroll_bars": "enabled",
     "tab_size": 2,
     "translate_tabs_to_spaces": true,
     "word_wrap": "true"
}
````

#### Remove Project
进入packadge所在的文件夹，local => Session.sublime_session用其他编辑器打开，找到"recent_workspaces”:，删除不想要的路径即可   

#### Vintage Mode
VIM mode, [detail](http://www.sublimetext.com/docs/2/vintage.html)    

#### Nettuts + Fetch
````html
ctrl + shift + p => fetch => Manage, File, Package
````

#### Copy Path
````html
ctrl + shift + p => copy => 
  File: Copy as Tag a
  File: Copy as Tag style
  File: Copy path from project encoded
````