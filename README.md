# RoBERTa-based Natural Language to SQL Query Generation
This repo contains the code for NL2SQL paper titled "Data Agnostic RoBERTa-based Natural Language to SQL Query Generation". The link to which is: https://arxiv.org/abs/2010.05243

Our code was based on the previous works introduced in the paper "Content Enhanced BERT-based Text-to-SQL Generation", the code to which can be found [here](https://github.com/guotong1988/NL2SQL-RULE). Also these codes are built on top of the codes written by https://github.com/DebadityaPal/RoBERTa-NL2SQL

## How to use the code
All the work is done in a Google Colab workspace with a GPU runtime accelerator, in order to reproduce the results it is recommended to run the code in a similar workspace. Thus we have created a notebook which can be found at this link. https://colab.research.google.com/drive/1UbeiT3lAQ_VeC2edL_Wmm3xQsh8RCBun?usp=sharing

## Below are the step by step instructions to run the models:

 1. Visit https://drive.google.com/drive/u/0/folders/1rXkV_bjnhJBOLhhCeBPwIgEqdLp0rdfi. This Drive contains all the datasets and pretrained model weights. **Add a shortcut to your drive.** 
 2. Open the notebook, the link to which is provided above.
 3. Make sure the runtime accelerator is set to GPU.
 4. Mount your Google Drive and clone this repository in the runtime environment, the code for this step has already been provided in the notebook.
 5. The Notebook is now ready for use. All the package requirements have been mentioned in the notebook.


## References

 - https://github.com/salesforce/WikiSQL
 - https://github.com/guotong1988/NL2SQL-RULE
