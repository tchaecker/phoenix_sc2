# Step-by-Step Guide to Installing Git on Windows 11 v1.0

## Introduction
Hey there! Welcome to the no-sweat, fun-filled ride to installing Git on Windows 11. Whether you're a newbie or a seasoned pro, we've got your back. So, let's get the party started! This guide is designed for Git 2.43.0 and it's version 1.0 (Release).

## Download the Git for Windows Installer
- Scoot over to [git-scm.com](https://git-scm.com/) and hit that "Download for Windows" button. It's the big green one—you can't miss it!
- Snagging this will hook you up with the freshest version of Git for Windows.

## Run the Installer
- Track down the file you just downloaded, likely named `Git-2.43.0-64-bit.exe`, and double-tap it.
- A setup wizard will appear, ready to take you through the options. We'll go through them together, so no stress!

## Choose the Desired Components
- You'll see a list of components to install. The defaults are pretty cozy for most, but here's a quick tour:
  - **Add a Git Bash Profile to Windows Terminal:** Tick this if you're chummy with Windows Terminal and want Git Bash in your terminal gang.
  - **Scalar:** If you're juggling a mammoth project, Scalar is your speed demon. Smaller projects? Skip it.

## Choose the Default Editor for Git
- Git's gonna ask for a text editor. Vim's on the table, but if it's not your jam, pick another like Notepad++ or Visual Studio Code. It's your editor sundae—top it as you like!

## Choose the Initial Branch Name
- Here's where you pick a name for the first branch in your repositories. "main" is the fresh "master," waving hello to an inclusive future in code land.

## Adjust Your PATH Environment
- The installer will quiz you about the PATH. Opt for "Git from the command line and also from 3rd-party software." Easy peasy.

## Choosing the SSH Executable
- This bit's about how you'll chat with other repositories. The bundled OpenSSH is your trusty sidekick here.

## Choose HTTPS Transport Backend
- "Use the OpenSSL library" should be pre-picked, and it's the ticket you want.

## Configure Line Ending Conversions
- Go for "Checkout Windows-style, commit Unix-style line endings" to play nice with others on different systems.

## Configure the Terminal Emulator for Git Bash
- MinTTY is your best bet for the terminal emulator.

## Choose the Default Behavior of 'git pull'
- "Fast-forward or merge" is the newbie-friendly choice. It's like training wheels for Git.

## Choose a Credential Helper
- The Git Credential Manager is already checked, and it's a keeper for stashing your login deets safely.

## Configuring Extra Options
- Next up, a couple of checkboxes for the adventurous:
  - **Enable File System Caching:** Keeps Git zippy when you've got a ton of files. Best to leave it checked.
  - **Enable Symbolic Links:** If you're not in the know on these, keep it unchecked to stay on the simple path.

## Enable Experimental Features (New Section)
- Ready to live on the edge? Git's got some fresh-out-the-oven features for the brave:
  - **Support for Pseudo Consoles:** Dive into running Python and other console apps right in Git Bash. It's still a bit green, though, so maybe hold off until it's ripe.
  - **Built-in File System Monitor:** Puts a turbo on Git commands in big projects. It's the new kid on the block, so brace for surprises, or play it safe until it's been around the block.

## Complete the Installation
- Smash that "Install" button and let the installation wizardry commence.

## Verify the Installation
- After the install fiesta, pop open Git Bash or Command Prompt and type `git --version` to see if it's ready to tango.

And voilà! You're now a card-carrying member of the Phoenix SC2 crew, where we're cooking up the spiciest SC2 replay analysis tool in the cosmos. If you get tangled up, just holler. We're here for you. Happy coding!
