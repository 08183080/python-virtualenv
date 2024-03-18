# python-virtualenv
Python的最佳实践是每个项目整个虚拟环境，实现环境隔离...
# try-log
## venv practice
```
python -m venv .venv
```
Then, you run:
```
.\.venv\Scripts\activate
```
But in my vscode settings, something wrong happens:
```
Activate.ps1 cannot be loaded because running scripts is disabled on this
system. For more information, see about_Execution_Policies at https:/go.microsoft.com/fwlink/?LinkID=135170.
At line:1 char:1
+ .\.venv\Scripts\activate
+ ~~~~~~~~~~~~~~~~~~~~~~~~
    + CategoryInfo          : SecurityError: (:) [], PSSecurityException
    + FullyQualifiedErrorId : UnauthorizedAccess
```
## pipenv practice
https://pythonguidecn.readthedocs.io/zh/latest/dev/virtualenvs.html
# commands
- [x] pip freeze > requirements.txt, 将当前虚拟环境中的所有包以及版本记录在requirements.txt中
