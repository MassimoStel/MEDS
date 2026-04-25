# MEDS

![main_infographic](./00-assets/images/main_infographic.jpeg)

## Overview

This repository contains the data and code related to the paper ""Math Education Digital Shadows for facilitating learning with LLMs:
Math performance, anxiety and confidence in simulated students and AIs".

## Models Included

* DeepSeek Chat
* Qwen3 4B (Thinking)
* Nemotron-3 Nano
* Ministral 3B
* Mistral Small 4
* Mistral Small 3.2
* Anita 24B (Uncensored)
* Qwen3 4B (Uncensored)
* Granite 4 Tiny
* Qwen3.5 9B
* Qwen3 4B
* Ministral 14B (Reasoning)
* Phi-4 (Reasoning+)
* Magistral Small
* Llama 3.2 MoE 18.4B
* Grok 4.1 Fast (Reasoning)

## Directory Structure

TODO: UPDATE THIS BEFORE FINAL RELEASE

```
├── 00-assets
│   └── images
├── 01-raw_data                      # Directory containing the raw data split by LLM (14 models).
│   ├── MANX_LLM_anitamistral
│   ├── MANX_LLM_DeepSeekLarge
│   ├── MANX_LLM_granite4h
│   ├── MANX_LLM_Grok41FastReasoning
│   ├── MANX_LLM_magistralsmall
│   ├── MANX_LLM_ministral14b
│   ├── MANX_LLM_ministral3b
│   ├── MANX_LLM_mistralsmall
│   ├── MANX_LLM_MistralSmall4
│   ├── MANX_LLM_phi4reasoning
│   ├── MANX_LLM_qwen34binstruct
│   ├── MANX_LLM_qwen35_9b
│   ├── MANX_LLM_qwen4bthink
│   └── MANX_LLM_qwen4bunce
├── 02-processed_data                # Directory containing the cleaned and processed data for use in downstream data analyses (2,000 personas for each of the 14 models, for a total of 10,000 files for each model (140K JSON files)).
│   ├── MANX_LLM_anitamistral
│   ├── MANX_LLM_DeepSeekLarge
│   ├── MANX_LLM_granite4h
│   ├── MANX_LLM_Grok41FastReasoning
│   ├── MANX_LLM_magistralsmall
│   ├── MANX_LLM_ministral14b
│   ├── MANX_LLM_ministral3b
│   ├── MANX_LLM_mistralsmall
│   ├── MANX_LLM_MistralSmall4
│   ├── MANX_LLM_phi4reasoning
│   ├── MANX_LLM_qwen34binstruct
│   ├── MANX_LLM_qwen35_9b
│   ├── MANX_LLM_qwen4bthink
│   └── MANX_LLM_qwen4bunce
├── 03-code                          # Directory containing the code used throughout the project.
│   └── 00-data_generation           # Code related to the data generation, includes the sampling distributions along with the weights used for each attribute.
└── 04-supplementary_data            # Contains additional re-elaborations of the processed data (mainly used to produce infographics and plots).
    ├── demographics                 # Contains a structured (tabular) overview of the attributes characterizing the synthetic human personas contained in the MEDS dataset.
    ├── sampled                      # Contains the list of run ids that were sampled from the raw data to ensure reproducibility.
    └── validations                  # Contains additional re-elaborations of the processed data  used for the purpose of validating the MEDS dataset split by Task number.
        └── task-2
        └── task-3
```
