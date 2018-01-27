# Git Hooks
Git has a way to fire off custom scripts when certain important actions occur. This repository intends to group the different scripts according to their specific language and functionality. When you need a hook you can come to this repository to look forward that functionality you need to control in your git flow.

Bug reports and pull requests are welcome

## How can I contribute
You can contribute to this repository in different ways:
- Giving feedback of ideas to implement
- Add new hooks to the repository
- Translate existing hooks into other languages
- Report bugs
- Sharing this repository publicly :)

To keep the repository organized we gonna follow this structure
### Language
The first structure level classify the language the script is done. We accept all kinds of languages.
### Trigger Name
The second structure level classify the trigger action this script is thrown.
If hook isnt in a concrete trigger category, just insert it in general folder
### Functionality
A meaningfull description of the usage of this hook, preferably dashed. Some examples:
- deploy-on-heroku (Deploy on Heroku)
- remove-debuggers (Remove debuggers)
- run-javascript-linter (Run Javascript linter)
- run-tests (Run test)
### Hook file
This is the script file that contains the code, in certain scripting language, that cover certain functionality.
#### Location:
/language/trigger/functionality/hook
### Hook README file
Here you can put all the information of your hook. To make this step easier you can follow the template HOOK_README.md under .github repository
#### Location:
/language/trigger/functionality/README.md

## Contributors
This is the list of contributors of this repository:
[rgondev](https://github.com/rgondev)
