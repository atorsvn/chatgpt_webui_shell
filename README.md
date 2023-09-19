# chatgpt_webui_shell
![Shell Image](https://raw.githubusercontent.com/atorsvn/chatgpt_webui_shell/main/ezgif.com-optimize%20(3).gif)
## install
```
git clone https://github.com/atorsvn/chatgpt_webui_shell.git
cd chatgpt_webui_shell
pip install -r requirements
```
## Run
```
python3 app.py
```

Just install a dev plugin in the chatgpt webui like you would any other

## Docker run
```
sudo docker build -t chatgpt_webui_shell:latest chatgpt_webui_shell/
sudo docker run -d -p 5001:5001 chatgpt_webui_shell:latest
```
