# websocket-fastapi-tutorial
fastAPIのWebSocketチュートリアル<br>
python 3.10以上使用

# 使用方法
## （仮想環境(venv)構築）
```
💬 Go to the home directory
cd
💬 Create a directory for all your code projects
mkdir code
💬 Enter into that code directory
cd code
💬 Create a directory for this project
mkdir awesome-project
💬 Enter into that project directory
cd awesome-project
```
venvインストール
```
sudo apt install python-is-python3
sudo apt install python3.10-venv
python -m venv .venv
```
venv起動
```
source .venv/bin/activate
which python
python -m pip install --upgrade pip
echo "*" > .venv/.gitignore
```
venv終了
```
deactivate
```

## fastapiインストール
```
pip install "fastapi[standard]"
```
## websocketsインストール
```
pip install websockets
```
## main.py起動
```
fastapi dev main.py
```