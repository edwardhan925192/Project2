# Project2 
**Main goal: predicting judgment**  
Overall process: Data preprocessing --> Data augmentation (back translation) --> Additional Masking --> Prediction.  
In the domain of instance recognition, we meticulously transformed the original term to 'wizard' and 'sorcerer' to ensure semantic precision. Recognizing the intricacies of advanced NLP tasks, we adopted data augmentation strategies, principally employing back translation. Our primary transition sequence was English-German-English, a choice made to preserve the original context while introducing diverse lexemes within analogous scenarios. As a culminating step, we incorporated word masking for specific terminologies that potentially serve as pivotal indicators for adjudicating the victors. This was designed to enable the model to grasp the phonetic nuances and implications of these critical terms.

# Deberta
![image](https://github.com/edwardhan925192/Project2/assets/127165920/56ebcdf9-de5e-4c2d-b831-72ce4df0786c)  
DeBERTa (Decoding-enhanced BERT with Disentangled Attention) is an advanced transformer-based model for natural language processing tasks. Introduced by Microsoft Research, DeBERTa improves upon the BERT and RoBERTa models by introducing two major innovations:

Disentangled Attention Mechanism: Traditional transformer models like BERT use self-attention mechanisms where the attention scores depend on dot-products of query and key vectors. DeBERTa disentangles the content and position in the attention scores by computing them separately and then combines them. This allows for more flexibility and fine-grained modeling of the attention mechanism.

Enhanced Mask Decoder: While BERT utilizes a simple feed-forward neural network for its masked language model, DeBERTa employs an enhanced mask decoder with a two-layer feed-forward network, improving the model's ability to understand and generate text in masked language modeling tasks.

Due to these innovations, DeBERTa has demonstrated state-of-the-art performance across a variety of benchmark datasets, surpassing previous models in tasks such as sentence classification, question-answering, and more.

Professionals and researchers interested in pushing the boundaries of NLP tasks should consider experimenting with DeBERTa due to its performance advantages and innovative approach to handling attention.
