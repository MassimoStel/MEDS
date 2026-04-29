## Directory Structure

```
.
├── demographics                         # Contains a single dataset with the main demographics for each simulated human in the MEDS dataset.
├── sampled                              # Contains a single JSON file containing the run ids that were randomly sampled in the final MEDS dataset.
└── validations                          # Contains a list of datasets supporting validations for each Task.
    ├── task-2                           # Contains a single compressed CSV file containing the supporting dataset for the validation of Task 2 (ridgeplots).
    └── task-3_edge_list                 # Contains edge list of the behavioral forma mentis network constructed for Task 3. The edge lists are at the individual (run id) level and can be aggregated to produce a model-level network.
        ├── MANX_LLM_anitamistral
        ├── MANX_LLM_DeepSeekLarge
        ├── MANX_LLM_granite4h
        ├── MANX_LLM_Grok41FastReasoning
        ├── MANX_LLM_magistralsmall
        ├── MANX_LLM_ministral14b
        ├── MANX_LLM_ministral3b
        ├── MANX_LLM_mistralsmall
        ├── MANX_LLM_MistralSmall4
        ├── MANX_LLM_phi4reasoning
        ├── MANX_LLM_qwen34binstruct
        ├── MANX_LLM_qwen35_9b
        ├── MANX_LLM_qwen4bthink
        └── MANX_LLM_qwen4bunce
```
