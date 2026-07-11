# Foundry Local

## Foundry Local CLI Installation

As per your OS and device, pick suitable installation here: https://github.com/microsoft/Foundry-Local/releases
Once installation is done, verify it using `foundry status` command in command prompt

## Installing model
Before loading the model, one can see the list of available models using `foundry model list`
Then respective model can be installed with `foundry model load qwen3-embedding-0.6b`. Here qwen3-embedding-0.6b is model name
Using Foundry CLI for model loading sets default cache location different than the cache location .net sdk will set. Therefore, in this example we have explicitely configured cache location.