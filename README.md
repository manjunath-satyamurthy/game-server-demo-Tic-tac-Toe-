# game-server-demo-Tic-tac-Toe-
#### A very simple multiplayer game server demonstration. Tic Tac Toe

## Setup instructions:

### step 1: Clone the git repo.

```shell
git clone https://github.com/manjunath-satyamurthy/game-server-demo-Tic-tac-Toe-.git
```
  
### step 2: Ensure you have python 2.7 and virtualenv installed

### step 3: install virtual environment in the gameserver/ folder
```shell
cd game-server-demo-Tic-tac-Toe-/gameserver
virtualenv env
```

### step 4: Activate environment:
```shell
. env/bin/activate
```
  
### step 5: install requirements
```shell
pip install -r app/requirements.txt
```
  
### step 6: Create users
```shell
python app/manage.py createsuperuser
```
#### follow the instructions to create user and repeat step 6 for multiple users
  
### step 7: Start server
```shell
python app/manage.py runserver
```
  
### step 7: Now open the url 127.0.0.1:8000 in 2 different browser windows and login in with the different user account just created.

