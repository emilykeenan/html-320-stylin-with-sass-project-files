## Requirements

### [Node.JS](https://nodejs.org/en/download/)

FIRST: check to see if you already have Node installed. Start a
command line program (`cmd.exe` or `powershell.exe` on Windows,
Terminal.app on Mac, `xterm` on Linux).

Verify that your `node` and `npm` commands are *new* enough by running
the commands:

```bash
node -v
npm -v
```

* your `node` version is at least 6 and
* your `npm` version at least 3.

If you have older versions, or if you get errors trying to run those
programs, then head over to https://nodejs.org/en/download and follow
the instructions for getting the LTS (Long Term Support) version of
node for your computer and follow the instructions to install it.

After you've done that, run the two commands above and make sure they
meet the requirements.

## Installing

Clone the project files

```bash
cd Desktop
git clone https://github.com/gdiminneapolis/html-320-stylin-with-sass-project-files.git sass-class
cd sass-class
npm install
```

The last command will take a little bit of time, depending on the
speed of your computer and the internet connection. Be prepared for it
to take 10 minutes, sometimes.

There will be warnings, but they shouldn't cause problems.

## Watching and Building the Project

From the command line / terminal prompt, run:

```bash
npm start
```

This will automatically launch a watcher to convert your sass files into css files and
display the updates automatically. It should launch the default browser for your computer
showing the project files, "Women in Computing".

Note: Normally, you'll just leave the watcher running while we work on
assignments. You can also stop the watcher at any time by typing
Control-C (^C, C-c) in the same terminal / command window the watcher
is running in. (On Windows, if asked "Terminate batch job (Y/N)?" type
"Y" and return. (There may be times when the watcher stops "watching"
for some reason so you may need to do this.)

## Working on the Exercises

After we complete an exercise and discuss it, we'll be pulling down a new branch to start
all together with a clean slate for the next exercise. You may want to save the work you
did on that exercise. You can do that easily since it's a Git repository with the first
two steps of the Git Dance and then prepare for the next exercise:

```bash
git add --all --verbose # Add changes to the index
git commit -m "My work on exercise 1" # commit the changes to the local repo
# we're skipping the 3rd part of the dance, you won't push any changes
#
# Now check out the next exercise:
git checkout -b exercise-02 origin/exercise-02
```
