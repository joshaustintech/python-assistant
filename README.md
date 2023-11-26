# python-assistant
Python development AI assistant built on CodeLlama

## Screenshot
![screenshot](Screenshot.png)

## Installation
- Install and run [Ollama](https://ollama.ai/) on your system.
- Create the model using the Modelfile in your terminal:
  ```bash
  $ ollama create python-assistant -f Modelfile
  ```
- Run the Gradio UI via Docker:
  ```bash
  $ docker compose up --build
  ```
  **OR** install and run with Python 3.11 or higher:
  ```bash
  $ pip install -r requirements.txt
  $ python main.py
  ```
- Open the UI in your browser at [http://localhost:7860/](http://localhost:7860/)

## Credits
These people have inspired the system instructions that are in the `Modelfile`
- [Sammi Turner](https://github.com/sammi-turner)
- [jordantgh](https://github.com/jordantgh)

Special thanks goes to [Matthew Berman](https://github.com/mberman84) for [this video](https://www.youtube.com/watch?v=rIRkxZSn-A8) on wrapping the Ollama API in a [Gradio](https://www.gradio.app/) UI.
