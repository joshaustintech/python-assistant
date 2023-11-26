
FROM ollama/ollama

COPY . .

RUN ollama serve
RUN ollama create python-assistant -f Modelfile