# Foundry Local

## What is Foundry Local?

Foundry Local is an end-to-end local AI solution for shipping applications that run entirely on your device. Use Foundry Local when you want to run AI locally, work offline, minimize latency, or keep data private. Your data never leaves the device, responses start immediately with zero network latency, and your app works offline. There are no per-token costs and no backend infrastructure to maintain.

Foundry Local runs on your users' own devices, so your app works offline and you don't need an Azure subscription.

## Foundry Local CLI Installation

As per your OS and device, pick suitable installation here: https://github.com/microsoft/Foundry-Local/releases
Once installation is done, verify it using `foundry status` command in command prompt

## Installing model
Before loading the model, one can see the list of available models using `foundry model list`
Then respective model can be installed with `foundry model load qwen3-embedding-0.6b`. Here qwen3-embedding-0.6b is model name
Using Foundry CLI for model loading sets default cache location different than the cache location .net sdk will set. Therefore, in this example we have explicitely configured cache location.

<img width="958" height="433" alt="FoundryModelList" src="https://github.com/user-attachments/assets/ad373f92-325d-4d0e-98b7-96b39235cbd7" />

Command to install a model
`foundry model load "qwen2.5-coder-0.5b-instruct-generic-cpu"`

