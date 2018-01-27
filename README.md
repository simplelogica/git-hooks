# Git Hooks

Git has a way to fire off custom scripts when certain important actions occur. This repository intends to group the different scripts according to their specific language and functionality. When you need a hook you can come to this repository to look forward that functionality you need to control in your git flow.

Bug reports and pull requests are welcome

## How can I contribute

To keep the repository organized we gonna follow this structure

### Language
The first structure level classify the language the script is done
### Trigger Name
The second structure level classify the trigger action this script is thrown
### Functionality
A meaningfull description of the usage of this hook. Some examples:
- Deploy on Heroku
- Remove debuggers
- Run linter
- Run test
### Hook file
This is the script file that contains the code, in certain scripting language, that cover certain functionality.
#### Location:
/language/trigger/functionality/hook
### README Hook file
Here you can put all the information of your hooks.
#### Location:
/language/trigger/functionality/README.md

## Contributors
This is the list of contributors of this repository:
[rgondev](https://github.com/rgondev)
