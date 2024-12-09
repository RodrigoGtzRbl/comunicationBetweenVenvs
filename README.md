This is an example with two environments connected with sockets like client and server, the server is the venv39 (python 3.9) with coqui TTS, where the model is created and could be reusable, optimizing the TTS time.
The client is the venv313 which sends text to the 'server' to be sintetized

The repository is configured to have all the docs except the /venv39/lib/ so to use it, you have to use the requirements file in venv39/

