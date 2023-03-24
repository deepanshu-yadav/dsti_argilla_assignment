# Instructions

1. Set up a anaconda environment.
conda create --name argilla_assignment python=3.9


2. Install Docker for windows. 

Install for this [link](https://docs.docker.com/desktop/install/windows-install/)
You might need to update your WSL from [here](https://learn.microsoft.com/en-gb/windows/wsl/install-manual#step-4---download-the-linux-kernel-update-package). 


3. Run the argilla container. 

```
   docker run -d --name quickstart -p 6900:6900 argilla/argilla-quickstart:latest
```


4. Go to browser and type localhost:6900 . Login User name argilla password 1234. 


5. Make an account on open-ai.  Go to https://platform.openai.com/account/api-keys and then make your key, copy this key and keep this as a secret. 


6. Install python packages using the following pip commands 

```
  pip install openai datasets argilla
```


7. Now launch a jupyter environment. 


8. Now run the notebook in thios repo one by one. Copy the key you obtained one by one.
