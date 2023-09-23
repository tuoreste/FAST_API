STEPS TO SETUP PYTHON ENV IN VSCODE

1. Installation of python(on MAC-OS): 
	
	brew install python

2. Creating environment for pyhton3

	python3.9 -m venv myenv

3. Activating environment

	source myenv/bin/activate
	(note that you need to activate your environment whenever you open your VS_CODE)

4. Installing fastapi

	pip install fastapi uvicorn
