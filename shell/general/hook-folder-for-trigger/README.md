# Hook folder for trigger

## Description
This hook runs various hooks in a subfolder, scripting language independent, ordered alfabethically

## Pre-requisites
None

## Installation
To use this hook just put it into your hooks folder, and rename it as the name of your hook (precommit, commit-msg, ...)
Create a folder that is named as the name of your hook plus ".d" and put there all your hooks of this trigger kind

Git this hook and hooks in your folder execution permissions
> chmod a+x /.git/hooks/pre-commit
> chmod a+x /.git/hooks/pre-commit.d/*

## Usage
Hooks are automatically thrown when you use your git commands!

Note: If folder name hook.d is not created, this main hook show a warning message when executed
Note: If one of the hooks inside the folder fails with exit status, this hook stops execution

## Uninstallation
If you want to skip this hook just remove execution access permissions and it wont be executed
Or just simply remove it on your hooks repository
