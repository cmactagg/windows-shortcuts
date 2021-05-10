# Windows
## Window Manipulation
maximize current window - `Windows+up`  
minimize current window - `Windows+down`  
dock current window to side of screen - `Windows+left|right`  
quit current app - `Alt+F4`  
open menu for active program - `Alt+spacebar`  
move window - `Alt+spacebar` then `M` then use arrow keys `<enter>` to drop  
toggle High Contract on/off - `Lalt+Lshift+PrintScreen`  

## Open/Select Window
open explorer - `Windows+e`  
show desktop - `Windows + d`  
search in start menu - `Windows+(type anything)`  
switch between open programs - `Alt+Tab`  
focus on program in toolbar - `Windows+[1-0]`  
- (install 7+ Taskbar Number - `https://rammichael.com/7-taskbar-numberer#:~:text=Alt%2BWindows%20logo%20key%20%2Bnumber&text=7%2B%20Taskbar%20Numberer%20adds%20numbers,the%20Windows%20key%20is%20down`.)
    - add -hidewnd -v2 arguments to the shortcut, and add the shortcut to startup


# Chrome
open new window - `Ctrl+n`  
open new tab - `Ctrl+t`  
open incognito window - `Ctrl+Shift+n`  
reopen last closed tab - `Ctrl+Shift+t`  
move to prev|next tab - `Ctrl+PgUp|Down`  
move to previous tab - `Ctrl+Shift+Tab`  
in browser history - `Alt+left|right back|forward`  
close current tab - `Ctrl+w`  
find - `Ctrl + f`  
reload current tab - `F5`  
cursor to search bar (Tab  to focus back on page) - `Ctrl+L`  
next clickable link, or input on page - `Tab`  

## Vimium
To show help - `?`  
### To copy text  
- `/` (then type search text) `<enter>` `n|N` to go to next|previous occurance
- `v` to go to Visual Mode
- `h|l` to select additional letters
- `j|k` to select additional lines
- And can use other vim movement keys
- `y` to yank (ie copy)

### With Visual Mode
- change to cursor - `c`
- or back to visual - `v`

### Cursor Movement (basic)
move left - `h`  
move right - `l`  
move up - `k`  
move down - `j`  
move right/forward one word - `w`  
move left/back one word - `b`  
move right/forward to end of current word - `e`  
move to start of line - `^` (not working)  
move to end of line - `$`  

# File Explorer
focus address bar - `Alt+D`  
focus search bar - `Ctrl+F`  
move up in the folder structure - `Alt+up`  
cycle through the areas - `Tab`  
to open a folder of file - `<enter>`  


# VS Code  
## Shortcut helpers
search for shortcut keys - `Ctrl+Shift+p`  
open shortcut editor - `Ctrl+k Ctrl+s`  

## Pane Navigation
select the screen split - `Ctrl+[1|2|…]`  
split screen - `Ctrl+\`  
focus terminal/editor toggle - `Ctrl+'`  
focus on project explorer - `Ctrl+Shift+e`  
close window - `Ctrl+w`  
focus on editor (2, 3, 4 for other splits) - `Ctrl+1`  
Open Markdown preview - `Ctrl+K V`  

## File Navigation
search bar for files in project - `Ctrl+p`  
cycle through list of open files - `Ctrl+Tab`  
cycle through file history - `Alt+[left|right]`  
create new file (when in explorer) - `Ctrl+Alt+n`   

## Editor Navigation
go to line - `Ctrl+g`  
go to previous cursor position - `Ctrl-u`  
go to definition of currently highlighted variable/function/ class - `F12`  
scrolling one line - `Ctrl+up|down`   
scrolling one page - `Ctrl+pgup|pgdn`

## Editor Manipulation
delete line - `Ctrl+Shift+k`  
move the current line up or down - `Alt+up|down`  
format document - `Ctrl+Alt+f`  
replace/rename all instances of highlight symbol with new value - `F2`  
select current block, use again for next bigger block (left for smaller) - `Alt+Shift+right`  

## Editor Helper
show the error message for the line (red underline) - `F8`  
show intellisense - `Ctrl+k Ctrl+I`  
Show recommended actions (like delete unused variable) - `Ctrl+.`  
peak at the definition of the currently highlighed variable/function - `Alt+F12`  
peak at all the references of a variable or function - `Shift+F12`  

## Search
open file outline - `Ctrl+Shift+o`  
search the whole project for a variable/method - `Ctrl+t`  
seach whole project - `Ctrl+Shift+f`  
find - `Ctrl+f`  
find next/previous - `F3`/ `Shift-F3`
find/replace - `Ctrl+h`
replace - `Ctrl+Shift+1`

next instance of search (within search) - `<enter>`  
exit search (within search) - `<esc>`  

# Markdown
[Markdown syntax source for VS Code](https://www.markdownguide.org/tools/vscode/#vscode-markdown-support)

Open Preview - `Ctrl+Shift+v`

Heading Level 1 - `# some text`  
Heading Level 2 - `## some text`  
Paragraph - just separate the text with a blank line.  
Carrage Return - end line with 2 or more `<spaces>` and a `<return>`  
Bold - `**some bold text**`  
Italics - `*italics text*`  
Bold and Italics - `***bold and italics text***`  
Block Quote - add `>` infront of paragraph, then a `blank line` below to end (multiple `>>` for nested)  
Numbered List - start line with `1.`   
Unordered List - start line with `-<space>`  `Indent` to start a nested list  
Code block - start line with `<tab or indent>`  
Code (single line) - enclose with ticks `` `like this` `` (if text includes ticks, then surround the whole text with double ticks)  
Image - `![alt text](path/to/image.png)`  
Link - `[link text](http://theurl.com "alt text")` [link text](www.google.com "fukin google")  
Quick link for url or email - surround with <> `<you@mail.com>`  
Horizontal Rule - `blank line` then `three underscores (___)` then `blank line`  









