
# Howdy, y'all! 🤠

Welcome to our lil' ol' GitHub repository. Here, we're gonna be usin' them fancy 
GPT-4 models provided by the kind folks over at Nomic AI and them tokenizers from 
Hugging Face.

## GPT-4 Model Download 🚜

If y'all are itchin' to get them models, well, you're in luck! Just head on over to 
this here link:

https://the-eye.eu/public/AI/models/nomic-ai/gpt4all/

## Tokenizer 🐍

Now, we're gonna need us a tokenizer to get this party started. You can find that 
right here:

https://huggingface.co/decapoda-research/llama-7b-hf/tree/main

## Scripts 📜

Y'all are gonna find some useful scripts in the `/submodules/pyllamacpp/pyllamacpp/scripts` 
folder. They're labeled like this:

convert_gpt4all.py
convert.py
migrate.py

To convert the file to a usable model with LangChain, run this here command in the 
scripts folder while in a virtual Python environment:

python convert_gpt4all.py ../../../models/gpt4all-lora-unfiltered-quantized.bin 
../../../submodules/llama-7b-hf/tokenizer.model 
../../../models/gpt4all-lora-unfiltered-quantized-fuckedwith.bin

## IPython Examples 🌽

We got some handy-dandy IPython files for y'all to see how to get them llama_cpp and 
gpt4all workin' together. Check 'em out in this here repository.

Y'all have fun now, ya hear! 🤠
