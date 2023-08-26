
# Add "Open Windows Terminal" action to windows explorer directory context menu

It's all about adding the "Open Windows Terminal Here" option to your right-click menu.

You know those moments when you're working with folders in Windows, and you just wish you could open the terminal right there, in that specific folder? Well, with this trick, you can do exactly that! No more hassle of manually opening the terminal and navigating through a bunch of commands. It's a real time-saver! 

But here's the thing: Windows actually embedded this feature a while back, but there are some cases where the "Open Windows Terminal Here" option doesn't show up in the context menu after installing Windows Terminal. But don't worry, because we've got a solution just for you!


## Installation

Double click on

```bash
  Add_Open_in_Windows_Terminal_expandable_context_menu.reg
```
You will be prompted whether you want to merge the reg file. Click on the “Yes” button and then the “Ok” button.

That is it. From now on, whenever you  Right-click in a directory or folder, you will see the new “Open Windows Terminal here” option in the right-click menu.

![screenshot](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgaDzoc8poRL66_hnhV25rtz6mzBXLsCdkHFJx1MoHW83I7mUMgI21xT5DFXCN9-aEkz3Og8RFGWuyjMJZH6z9UcwcB2wbeXaBx4ZPQa9elaGAqnrZTKdrPP1KD46Ob2caTPnHO9g4qnHVJiPw1nFwNNCM6p4yBhJUSANTUPQF_D7epWuejStkJGXQ2HPfL/s1920/screenshot-cmOpenwindowstermhere.jpg)

## (Optional) Add icon to the Option
Open the Run dialog box by pressing Win + R shortcut. In the blank field, copy and paste the below path and press Enter.
```bash
  %USERPROFILE%/AppData/Local/
```
After the directory opens, copy the "cmOpenTerminal" folder to the currently open directory.

that is it. From now on, you should also see the terminal icon right next to the “Open Windows Terminal here” option.

## How to Uninstall?
You just double click on remove file.
```bash
  Remove_Open_in_Windows_Terminal_expandable_context_menu.reg
```
## Thanks to

- [@kerol2r20](https://github.com/kerol2r20)
- [Windows 11 Forum](https://www.elevenforum.com/t/add-or-remove-open-in-terminal-context-menu-in-windows-11.2479/)
