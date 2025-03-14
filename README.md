# IDL-Project

Code to run the pruning methods:
```
python main.py \
    --model meta-llama/Llama-2-7b-hf \
    --prune_method wanda \
    --sparsity_ratio 0.5 \
    --sparsity_type unstructured \
    --save out/llama2_7b/unstructured/wanda/
```
