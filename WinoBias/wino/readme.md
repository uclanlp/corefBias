---
## WinoBias dataset ##
1. The data/ folder contains the WinoDataset we generated.
2. Gender swapping lists are listed in extra_gendered_words.txt and generalized_swaps.txt files. The swapping can be finished by the word_swapper.py file.
3. If you want to try the WinoBias dataset using [allennlp](https://allennlp.org/models), remember to add "pos_tag != '-'" in line 274 [here](https://github.com/allenai/allennlp/blob/5f9fb419273f99c949ccdabab22fdc8e9b895c1c/allennlp/data/dataset_readers/dataset_utils/ontonotes.py#L274).
