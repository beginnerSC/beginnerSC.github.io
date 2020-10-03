# [Cloud JupyterLab Workspace Launcher](https://beginnersc.github.io/)

* "Launch with password" unchecked: Can only pull public repositories
* "Launch with password" checked: Can pull public or private repositories
   * Internally it uses nbgitpuller with a token
   * The advantage opening public projects with a token is that when pushing code change back to GitHub there is no need to type in ID and password
* If Launch Empty, all input fields will be ignored
* Things to look out for: 
  * This launcher can only pull repositories from this account because GitHub ID is hard coded in the url. To pull from other accounts, use [this launcher](https://yc14e.github.io/) instead
  * The repository to be pulled must have a master branch. A "main" branch or anything else wouldn't work. Pulling master branch is hard coded in this launcher as of now
