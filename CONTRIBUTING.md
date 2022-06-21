# Contributing to Grafana API Collection

  Thank you for your interest in contribute to this project! All people who want to contribute in a healthy and constructive manner within our community are welcomed. To help create a safe and positive community experience for all, participants are required to adhere to the [Code of Conduct](CODE_OF_CONDUCT.md).

### How do I...
  - [Contribute code](#contribute-code)
  - [Set up the project](#set-up-the-project)
  - [Export to postman format](#export-to-postman-format)

## Contribute Code

  To contribute code:
  
  1. Check if there's an already existing issue that describes the reason or motivation behind your pull request.
  2. If there are no issues describing what to do, go ahead and [create one](https://github.com/gjed/grafana-api-collections/issues/new/choose). By creating an issue before you start working on a fix, you can increase the chance of your pull request getting accepted! 💪
  3. Now you're ready to [open a pull request](https://github.com/gjed/grafana-api-collections/compare)!
  4. In the description for your pull request, add a line that says `Fixes #456`, where `456` is the number of the issue the pull request Fixes
  
  After you've created the pull request:
  
  - If the maintainer askds for any changes, edit your changes, push, and ask for another review.
  - If the maintainer decides to pass on your pull request, they will thank you for the contribution and explain why they won't be accepting the changes
  - If your pull request gets accepted, it'll be merged into the main branch soon after. Your contribution will be available in the next release! 🎉
 
### About commit messages
  You can reference [this page](https://www.freecodecamp.org/news/how-to-write-better-git-commit-messages/) for a template for the commit message.

  For examples:
  ```
  fix: fix method in admin api 

  This fixed the wrong http method for this api in this collection

  Fixes #456
  ```
## Set up the project

  > It is strongly recommended to use VSCode for this project

  To setup the project:

  1. Clone the repository
  2. Install the suggested VSCode extensions (Thunder Client and REST Client)
  3. Check that the workspace configuration is set up correctly:
      - The Thunder-client extensions uses this vscode setting to know where the collection is located `"thunder-client.customLocation"`. Modify the `.vscode/settings.json` and specify the correct path. Please refer to the [original documentation](https://github.com/rangav/thunder-client-support#team)

## Export to postman format

The Thunder Client extension allows you to export the collection in postman format. This will export the collection to postman v1 format. If you need to export to postman v2 format, check the [official documentation](https://learning.postman.com/docs/getting-started/importing-and-exporting-data/#converting-postman-collections-from-v1-to-v2) on how you can migrate from v1 to v2.
