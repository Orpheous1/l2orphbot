# L2Orphbot

## Getting Started

Precompiled binary : [l2orph.exe](https://mega.nz/file/LVpBlSKa#4kmdVlP_vZL13exF64ubNMG_CpuZ-UtOZPebcSz7WFc) download the .exe and run it with administrator privileges(right click->run as administrator)

Otherwise download the whole project from this git and run l2orph.exe


## Usage

Sends the following keystrokes with 0.5 sec delay sequentially: `del, end, page_down`
You can change these keybinds from settings->shortcut and map them to Shortcut(Expanded #) and place in the 3rd bar the following macros:

macro1 at 1st place of 3rd bar:
`/target tankname`
`/assist`
`/attack`

macro2 at 2nd place of 3rd bar:
`/assist`
`/assist`
`/assist`

macro3 at 3rd place of 3rd bar:
`/attack`
`/assist`

This works even when l2 is in the background. I've found that interchanging macro1 and macro2 at the bar works better when l2 is in the foreground.

### Tweaking the bot

If you want to change the buttons edit `l2orph.py` and either install the dependencies
* python3.7
* win32gui
* win32con
* win32api
* tkinter

and run the `l2orph.py` script with a .bat file calling the interpreter with administrator rights

or edit `l2orph.py`, download pip and the dependencies above and

`pip install auto-py-to-exe` in cmd, then run `auto-py-to-exe` in cmd.

Then run the exectuable with administrator rights.
