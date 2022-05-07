---
title: "Neural Network From Scratch"
date: 2022-04-30
classes: wide
tags: [neural network, backpropagation, ai, machine learning]
---
I started learning machine learning and deep learning without any strong foundation. I went directly into the implementation, without properly understanding the maths. I would not say that it was the best approach, but it was effective. But, deep inside I always had this uneasiness of not understanding completely the thing I was doing. This blog is my attempt to understand the maths behind the neural networks and build a neural network from scratch using python. 

A lot has been said and written about neural network. My goal here is not reiterate the things you already know, my goal is to explain the "complex math" (double quotes because it's not actually) behind them in simple language that is easy to grasp and explain it in a way that it would be easy to code too.

### Introduction
Just for the context a brief introduction:
>A neural network is a series of algorithms that endeavors to recognize underlying relationships in a set of data through a process that mimics the way the human brain operates

The neurons are the building blocks of neural network. In reality they are just some mathematical function that transforms the input data. So, in simple terms what neural network does is take any input (which is some sort of data) and using neurons (or mathematical functions) map it to an output. And, when we say we are training a neural network it means that we are trying to figure out this mapping. A simple neural network would look like this:

<img src ="https://raw.githubusercontent.com/ashutoshrawat/ashutoshrawat.github.io/master/assets/images/nn_from_scratch/simple_nn.png" width='500' height='500' align='center'/>
<center>Fig: Single dense layer perceptron network</center> <br/>

