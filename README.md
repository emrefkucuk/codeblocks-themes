# A guide on installing themes for Code::Blocks
The Code::Blocks IDE does not have different themes by default and uses the original Windows color theme and most of the articles about installing themes in Code::Blocks lead to dead links and incomplete tutorials, this guide aims to fix that.
# Installation Steps (for Windows only):
1. Download the `colour_themes.conf` config file from [this gist](https://gist.github.com/yzhong52/6852140faa233408de67). All credit for the file goes to [the author](https://github.com/yzhong52)
2. Make sure Code::Blocks is not running.
3. Search for "CodeBlocks Share Config" and run it, by default it should be in `C:\Users\your-username\AppData\Roaming\Microsoft\Windows\Start Menu\Programs`.
4. At the left side, load your `colour_themes.conf` and at the right side, load `default.conf` found by default in `C:\Users\your-username\AppData\Roaming\CodeBlocks`.
5. Tick all the boxes on the left and click __Transfer__, confirm.
6. Click the __Save__ button at the bottom and confirm.
7. Run _Code::Blocks_, go to `Settings -> Editor -> Syntax Highlighting -> Colour Theme` and voila! You can choose from the themes installed.
8. If you're a real programmer and chose a dark theme, the keyboard cursor will be invisible to you since it is black by default. To fix this,
`Settings -> Editor -> Margins and Caret -> Change the caret color to white`

And you're done! Enjoy the variety of themes.
