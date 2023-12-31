# Machine Learning Batch #2

[👍FB group: ML with Towhid](https://www.facebook.com/groups/144446068732805)
[👍YouTube : Nurul Akter Towhid](https://www.youtube.com/@DSwithTowhid)


# Class #2
1. Install git : https://gitforwindows.org/
2. 🐍 pyenv install & cheat-sheet

   ##### Windows

   - Open windows powershell and run this command:
       ```pwsh
       Invoke-WebRequest -UseBasicParsing -Uri "https://raw.githubusercontent.com/pyenv-win/pyenv-win/master/pyenv-win/install-pyenv-win.ps1" -OutFile "./install-pyenv-win.ps1"; &"./install-pyenv-win.ps1"
       ```

   - If you are getting any **UnauthorizedAccess** error as below then start Windows PowerShell with the **Run as administrator** option and run -
       ```pwsh
       Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope LocalMachine
       ```
   - Then re-run the previous powershell link code.
   - For more details visit this [link](https://github.com/pyenv-win/pyenv-win/blob/master/docs/installation.md#powershell).

    ##### Linux
     - If you wish to install a specific release of Pyenv rather than the latest head, set the PYENV_GIT_TAG environment variable (e.g. export `PYENV_GIT_TAG=v2.2.5`).
        ```sh
        curl https://pyenv.run | bash
        ```

   - For more details visit this [link](https://github.com/pyenv/pyenv-installer).
    <br>

    ##### Cheat-sheet
    Here's a cheat sheet of some commonly used commands with pyenv:


    - To list all the available Python versions that can be installed with pyenv:

        ```sh
        pyenv install --list
        ```
    - pyenv install: Install a specific Python version.


        ```sh
        pyenv install <version>
        ```
    - pyenv versions: List all installed Python versions.

        ```sh
        pyenv versions
        ```
    - pyenv global: Set the global Python version to be used.


        ```sh
        pyenv global <version>
        ```
    - pyenv local: Set a Python version for the current directory.


        ```sh
        pyenv local <version>
        ```
    - pyenv shell: Set a Python version for the current shell session.


        ```sh
        pyenv shell <version>
        ```

    - pyenv uninstall: Uninstall a specific Python version.


        ```sh
        pyenv uninstall <version>
        ```
    - pyenv rehash: Rehash the installed executables.


        ```sh
        pyenv rehash
        ```
    - pyenv which: Display the full path to the executable of a Python version.

        ```sh
        pyenv which <version>
        ```
    - pyenv exec: Run a command using a specified Python version.

        ```sh
        pyenv exec <version> <command>
        ```
3. Install python 3.8.6 using pyenv (using commands in cheat-sheet)
4. Install vscode (https://code.visualstudio.com/download)
5. Install following extentions in vscode:
    ```sh
    chrmarti.regex
    donjayamanne.githistory
    dzhavat.bracket-pair-toggler
    eamodio.gitlens
    GrapeCity.gc-excelviewer
    humao.rest-client
    ionutvmi.path-autocomplete
    iterative.dvc
    mechatroner.rainbow-csv
    ms-azuretools.vscode-docker
    ms-python.autopep8
    ms-python.flake8
    ms-python.isort
    ms-python.pylint
    ms-python.python
    ms-python.vscode-pylance
    ms-toolsai.jupyter
    ms-toolsai.jupyter-keymap
    ms-toolsai.jupyter-renderers
    ms-toolsai.vscode-jupyter-cell-tags
    ms-toolsai.vscode-jupyter-slideshow
    ms-vscode-remote.remote-containers
    ms-vscode-remote.remote-ssh
    ms-vscode-remote.remote-ssh-edit
    ms-vscode.remote-explorer
    njpwerner.autodocstring
    PKief.material-icon-theme
    Shan.code-settings-sync
    shardulm94.trailing-spaces
    shd101wyy.markdown-preview-enhanced
    VisualStudioExptTeam.intellicode-api-usage-examples
    VisualStudioExptTeam.vscodeintellicode
    wayou.vscode-todo-highlight
    yzhang.markdown-all-in-one
    ```

6. Install and create virtual environment:

    ```sh
    pip install virtualenv
    python -m venv ml_dl_env
    ```

   - Activate it:
       Linux:
       ```sh
       source ml_dl_env/bin/activate
       ```
       Windows:
       ```
       C:\Users\path\ml_dl_env\Scripts\activate
       ```

# Class #3
- Revisit DataTypes, Control Structure, Dynamic vs Static Typing
- Python Functions, Docstring, Lambda function
- Tutorials code added

# Class #4

- Python Class
- OOP in python
- Design Patterns : https://refactoring.guru/design-patterns

# Class #5
- dataset selection : https://www.kaggle.com/datasets/kartik2112/fraud-detection/code

# Class #6
- Basic idea about NumPy
- Vectors, Arrays, Matrices
- Number generation
- Array Attributes and Methods
- Selection, Indexing
- NumPy Operations
- NumPy input & output

# Class #7
- Basic about Pandas
