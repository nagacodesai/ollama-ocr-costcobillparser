# Ollama-OCR
Ollama-OCR

First install the ollama exe in windows as local llm.

Post than create an virtual env and then

once ollama is enabled download the models.

ollama pull llava:7b 
ollama pull llama3.2-vision:11b

To check cuda compatiility with pytorch :

nvcc --version
nvidia-smi
goto https://pytorch.org/
check version compat and derive pip command.
pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121