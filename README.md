# repoFromCLI-GHAPI

* Create a GitHub repo from the Command-Line Interface (CLI).

    `$ curl -u '<user_id>' https://api.github.com/user/repos -d '{"name":"repoFromCLI-GHAPI"}'`

* Create a new repository on the command line

    ```
    echo "# repoFromCLI-GHAPI" >> README.md
    git init
    git add README.md
    git commit -m "first commit"
    git remote add origin git@github.com:<user_id>/repoFromCLI-GHAPI.git
    git push -u origin master
    ```

* Push an existing repository from the command line

    ```
    git remote add origin git@github.com:<user_id>/repoFromCLI-GHAPI.git
    git push -u origin master
    ```
