# Hands-on-With-Huggingface


# Table of Contents
- [Intro](#intro)
  - [Why Should I Read This](#Why-Should-I-Read-This)
  - [Prerequisites](#Prerequisites)
- [The HuggingFace Landscape](#The-HuggingFace-Landscape)
- [End to End Huggingface Project](#End-to-End-Huggingface-Project)
  - Setting up a working environment
  - Get Data
    - Explore Data 
  - Prepare Data
  - Select a Model
  - Train and Evaluate model results 
  - Exercises



## Intro
### Why Should I Read This <a name="Why-Should-I-Read-This"></a>
This repo will be a hands on way to learn the popular NLP library [Huggingface](https://huggingface.co/) while there are plenty of resources already online for example https://huggingface.co/course/chapter0/1?fw=tf that is well written and straight from hugging face themselves, so natruly the next question is why read my guid well my goal is to make a more hands on approach to learning this subject. I will do this by taking an example driven approach to this study guide, as well as put in examples you can try by yourself at the end of each chapter/section(I will also do the example myself incase you want to check your work and if you think your answer is better let me know, I am always looking for better ways to do things). The main goal of this guide is to give you the ability to create machine learning projects using hugging face so you can have another great tool in your machine learning tool kit.

### Prerequisites <a name="Prerequisites"></a>
This study guide assumes you know some basic machine learning and as well as some python, and you need to want to learn more about NLP/Huggingface. You should know how to make functions as well as the basics of neural networks.

### What Will You Learn
the goal of this guid is to teach you four main ideas:
1. A basic understanding of NLP and HuggingFace and why they are so important 
2. How to build text based models not using HuggingFace
3. How to use HuggingFace's transformers
4. How to fine tune a pretrained models

## The HuggingFace Landscape  <a name="The-HuggingFace-Landscape"></a>
"The AI community building the future. Build, train and deploy state of the art models powered by the reference open source in machine learning." I got this quote from the home page of the HuggingFace website while this sounds nice and all it doesn't tell you what you can use hugging face for, so that's why I am here, the main use case of HuggingFace is using there pretrained models for NLP tasks they have many different type of text based models that are pre trained on millions of gigabytes of text data that would take you weeks if not months to train (depending on your machine). Lucky HuggingFace offers many free pretrained transformers that you can fine tune to any task you want, this has a few great benefits such as:
  - It will take less time to train because it was already pretrained
  - The results will probably be more robust 
  - You don't have to spend a bunch of money training a new model


### What is NLP
NLP stands for natural language processing and it basically means using computers and programing to work with text data. The next question is what kind of things would we want to use NLP for, well there is a lot one common example is Siri, siri uses NLP to convert what you tell her into a language computers can understand (numbers). While there are a bunch of different use cases of NLP we will mostly focus on Classifying whole sentences, Classifying each word in a sentence, Generating text content, Extracting an answer from a text, and Generating a new sentence from an input text (if you dont get what all of these mean dont worry wee will go over it later). Learning all these methods will also help you be able to extract the info you learned here and reapply it to any NLP task you come by.



## End to End Huggingface Project <a name="End-to-End-Huggingface-Project"></a>
In this section we will build an end to end Huggingface project where you will learn:
- set up an environment and install hugging face
- get text data as well as do some analysis on it
- use Huggingface pipeline to make some NLP models

and after you finish reading this chapter you can try and do the exercises and test how well you understood the material 

## NLP Models with Tensorflow (RNNs & LSTMs)

## Transformer models

## Using Huggingface Transformers

## Fine-tuning a pretrained model
