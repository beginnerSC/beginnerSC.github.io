# [Cloud JupyterLab Workspace Launcher](https://beginnersc.github.io/)

* "Launch with password" unchecked: Can only pull public repositories
* "Launch with password" checked: Can pull public or private repositories
   * Internally it opens the link with nbgitpuller with a token
   * The advantage opening public projects with a token is that when pushing code change back to GitHub there is no need to type in ID and password
* If Launch Empty, all input fields will be ignored
