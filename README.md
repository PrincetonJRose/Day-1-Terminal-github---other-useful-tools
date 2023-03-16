# Day-1-Terminal-github-and-other-useful-tools
To start your dive into the world of being a software engineer & developer, let's get more comfortable with some of the tools you'll be using to code!!!

## Terminal Commands ( No GUI for you... 🫵 )

These are some of the more common commands you'll use in the terminal as a software engineer! Don't worry to much about memorizing them, but it is handy to keep this list somewhere close by! Give some of these a try in your terminal and see the results for yourself!

> `pwd` ( print working directory ) - will show the current directory you're in

> `ls` ( list ) - will list the contents of the current directory, **You can use `ls -a` to show all files, even hidden ones!**

> `mkdir` ( make directory ) - allows you to make a new directory. **Takes an argument for the name of the new folder, i.e. `mkdir MyNewFolder`**

> `cd` ( change directory ) - used to move to a different directory. **Takes an argument for the name of the directory you want to go down into, i.e. `cd MyNewFolder`.**  Use `cd ..` to move up one 'level'. Can be chained with multiple `/` to move through multiple directories at once!

> `touch` - will make a new file in the current directory. **Takes an argument for the name of the file, i.e. `touch MyNewFile.txt`**

> `rm` ( remove ) - used to delete content. **Takes an argument for what to delete, i.e. `rm MyNewFile.txt`**

> `alias` - allows you to create shortcuts and save them in a variable in your terminal configuration file. **Very advanced, don't mess with these to much early on.** Useful as you get more comfortable though!!!

**Another quick note: you can use autocomplete to fill in the names of things when typing into the console using the `Tab` key!!!**

If you'd like to practice your terminal prowess, try out this lab here: https://github.com/learn-co-curriculum/terminal_warmup_2_chi_ds

## VS Code ( Your new IDE, or Integrated Development Environment )

Before we get started with writing new programs, one of the first things you should do is change your auto save settings in VS Code! You can change it to whatever you like, so try out all the options and see which one you think is best! I personally like to use the `onFocusChange` setting so that whenever I click outside the current tab it saves my work! **Auto-save is invaluable and should ALWAYS BE ON!!!**

> `Ctrl + ~` ( Control + Tilde ) - will open/close the terminal window

> `Ctrl + S` ( Control + S ) - will save the current file! If you have on auto save, you'll rarely have to use this. Still good to be in the habit of manually saving though!

> On Windows computers: `Alt + ⬆️` or `Alt + ⬇️`
  or on Macs: `Option + ⬆️` or `Option  + ⬇️`
    - allows you to either shift the line that the cursor is currently on or highlighted code, up and/or down in the editor window.

> `Ctrl + /` - allows you to comment out the current line the cursor is on or any highlighted code! Super useful!!! **You'll use this one all the time!!!**

> `Ctrl + P` - allows you to search for a file in the current project. This is also super handy and is one you should get used to using when your projects get bigger!

## VS Code Extensions

These guys are super helpful little modules that VS Code can install to make your life as a coder easier. There are tons of extensions that do lots of things, such as giving templates of code with snippets, or allowing HTML tags to close for us. There is no end to what they can do! Lots of developers use different extensions based on their personal needs, so don't hesitate to browse through what's available and try them out!

Here are some of the extensions I use:

- `Intellicode` by Microsoft - adds in AI support to help you with autocomplete. Super useful and integrates well into our IDE.
- `Code Spell Checker` by Street Side Software - the name says it all! Very handy since I hate always trying to remember how to spell things!
- `Indent Rainbow` by oderwat - makes indents not only look pretty, but it becomes easier to spot when things aren't aligned. Will be great when we get to Python!!!
- `Auto Close Tag` by Jun Han - automatically closes HTML tags for us. Can be helpful, but some might find it annoying.
- `Thunder Client` by Ranga Vadhinemi - allows us to make requests to servers right inside VS Code without needing an external program! Super useful!!!
- `vscode-icons` by VSCode Icons Team - changes the icons to be more recognizable at a glance in the left-most file explorer pane. Handy, but not necessary.

**Extensions are great! But don't get to trigger happy with them! Some of them can really slow down your computer, or outright make coding harder for you ( i.e. one that always tries to give you the wrong code snippets or autocomplete 😣 ).** They can always be uninstalled just as easily as you installed them, so you're not stuck with one if you don't like it.

## Dev Tools - Your Web Browser's way of helping you make great websites!

In every web browser there are a set of tools to help web developers with creating their websites and apps. You may have even seen them before by total accident! They are something we're going to live by as we work our way through this course. So get comfortable using them!!! 👍

There are two super common ways of opening the dev tools in your web browser:

1. `F12` or `Fn + F12` - the fast keyboard shortcut
2. `Right-click` on any webpage with your mouse ( or two finger click with a track-pad ), and in the new context menu that's popped up click `Inspect` all the way at the bottom.

You'll notice there is a lot going on here, but these tools really let us see behind the curtain of what's going on with **any** website we visit! Just know that the two most common things we'll look at most will be the `Elements` pane and the `Console` pane. But otherwise, feel free to take some time to explore around a bit and see what you can find! 🕵️

The last thing we'll set up for our dev tools is some more extensions, this time for our browser! You'll want to head to the Chrome web store and find these two extensions and install them:

- React Developer Tools
- JSON Viewer

We won't use them in this phase, but they will come in handy in future phases!!!

