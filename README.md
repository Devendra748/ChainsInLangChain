# ChainsInLangChain

This repository contains implementation examples and usage instructions for different chains in LangChain, a Python library for building conversational AI systems using language models.

## Table of Contents

- [LLMChain](#llmchain)
- [Sequential Chains](#sequential-chains)
  - [SimpleSequentialChain](#simplesequentialchain)
  - [SequentialChain](#sequentialchain)
- [Router Chain](#router-chain)

## LLMChain

LLMChain is a chain that uses the LangChain library's `ChatOpenAI` model to generate responses. It requires a prompt template and can be used for various conversational tasks.

## Sequential Chains
Sequential Chains are a composition of multiple LLMChains that are executed in a sequence. They can be used for multi-step conversational tasks.

## SimpleSequentialChain
SimpleSequentialChain is a sequential chain with two LLMChains. The output of the first chain serves as the input to the second chain.

## SequentialChain
SequentialChain is a more flexible sequential chain that can have multiple LLMChains and define custom input and output variables for each chain.

## Router Chain
Router Chain is a chain that selects a specific prompt template based on the input. It uses a multi-prompt router to determine the best prompt for the input and executes the corresponding chain.

This README provides an overview of the different chains available in LangChain and includes example usage for each chain. 
