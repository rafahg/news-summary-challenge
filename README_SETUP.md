## SETUP FOR THE THE PROJECT.

1. Create the folder structure. /lib for the actual implementation and
test for the test framework and the the tests.

2. Install http-server to run the app in the browser:
    - In the root of the project, in this case in /news-summary-challenge
    ```
    $ npm install http-server --save 
    $ node node_modules/http-server/bin/http-server
    ```
    By default the web will be displayed at //localhost:8080

3. As good practice, remove  node_modules of git control, to do this.

    ``` 
    touch .gitignore && echo "node_modules/" >> .gitignore && git rm -r --cached node_modules ; git status
    ```
    This command will create a .gitignore file if it does not already exists, add to the file the nodemodules directory and any other subfolder. 
    git rm -r --cached removes node_modules folder from git control if it was added before.
    git status displayed the new changes.






   
