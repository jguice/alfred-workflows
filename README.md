# Alfred Workflows
This repository contains workflows for the Alfred productivity app https://www.alfredapp.com/

## today
This workflow will help you record the day's accomplishments!

It appends whatever text you provide to a text file dated with the current date in a folder of your choosing.  Each line is prepended with a markdown unordered list marker `-` for easy copy/paste into a separate doc.

This can be helpful for daily standups, documenting billable work, or just reflecting on accomplishments (which is very important!).

Whenever you realize you just completed a task, or did something that seems worthy of note, etc. jot it down quickly before going on to the next thing. :running:

Even when about to "context switch" to another major effort it's good to just take a note of what you were doing.  Sometimes those items get lost in the shuffle.

Don't worry too much about keeping the file neat.  Since it's just a plain text file you can always go back and consolidate entries later, etc.


### setup
After [importing the workflow](https://www.alfredapp.com/blog/tips-and-tricks/tutorial-importing-and-setting-up-alfred-workflows/) double-click the bash script and find the line that looks like this (near the top):
```bash
path="/Users/..."
```

Change that to the directory (full path) you want files to be created in.  Make sure the directory exists. :smile:

### usage
Launch alfred, then type `today` followed a space and whatever text you want to append to the file.

Press enter, then check the directory you chose during setup.

You should see a new file with your text appended.
