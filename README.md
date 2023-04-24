## CCGRA: Smart Contract Code Comment Generation with Retrieval-enhanced Approach

### Dependencies
* python3.8
* torch
* numpy
* jsonlines
* faiss-gpu
* Levenshtein
* git+https://github.com/Maluuba/nlg-eval.git
* tensorboard
* tree_sitter

### Example Usages
Retrieval Module
```shell
cd retrieval && 
python bert_whitening.py && 
python main.py --type test && 
python main.py --type train &&
python main.py --type valid &&
cd ..
```

finetune CodeT5
```shell
cd CodeT5/sh && 
python run_exp.py --model_tag codet5_base --task summarize --sub_task solidity && 
cd ..
```

eval
```shell
python eval.py
```




