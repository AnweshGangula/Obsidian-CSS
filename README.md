# Obsidian Settings
All my obsidian settings and customizations

This repository is a copy of the entire `.obsidian` folder from my local Obsidian vault

## How to use?
* Clone this repository locally - to any location
* Copy all the contents of this repository (including `.git/` folder and `.gitignore` file) to the `.obsidian` folder of your respective vault

> **Note**: <br>
> * copying the `.git/` and `.gitignore` folder allows you to pull/push any changes to the GitHub respository <br>
> * Additionally, you can create branches to manage settings for multiple use-cases

## ignored files
* the `workspace` file is ignored since it is relevant to the respective vault.
    * below lines used in `.gitignnore` to [ignore files without extension](https://stackoverflow.com/questions/5711120/gitignore-binary-files-that-have-no-extension):
        ```sh
        # Ignore all
        *

        # Unignore all with extensions
        !*.*

        # Unignore all dirs
        !*/
        ```
