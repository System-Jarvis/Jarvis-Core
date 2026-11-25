# Version 1 Chainlit Web UI activation and access:

## Activation from terminal

Begin by entering the `~/Jarvis/app` directory.

```bash
cd ~/Jarvis/app
```

Activation of the environment comes from the `venv` that is located in the `~/Jarvis/venv/bin/activate` directory.

```bash
source ~/Jarvis/venv/bin/activate
```

Then conclude with the final command to open the web ui using `chainlit`.

```bash
chainlit run frontend.py -w --host 0.0.0.0
```

So in total, the complete command set is

```bash
cd ~/Jarvis/app
source ~/Jarvis/venv/bin/activate
chainlit run frontend.py -w --host 0.0.0.0
```


## Accessing the web environment

Once the `chainlit` has been run, it can be found at either address below:
```
http://jarvis:8000
or
http://100.87.127.100:8000
```

It is only accessible from devices with Tailscale VPN access.


## Important files which may be changed

The main file running the web environment is currently `frontend.py` located in the `~/Jarvis/app` directory. It runs the main functions of the server including the system prompt, health report data, functions the AI can pull, and time data.

`chainlit.md` is a necessary file for running chainlit, however it is completely blank at the moment. Anything put into that file would appear as a "welcome message".

`jarvis.css` located in the `~/Jarvis/app/public` directory holds the main contents of the CSS code which is used to provide a more pleasant experience in the web UI. The program calls files from the `~/Jarvis/app/jarvis_chainlit_theme` directory to make the program more pleasing to the eyes, so any modifications to that directory or to the `jarvis.css` file will affect the user experience.
