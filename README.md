# NER-BERT

This repository contains the collected large-scale named entity recognition (NER) corpus for pre-training in the paper: [NER-BERT: A Pre-trained Model for Low-Resource Entity Tagging](https://arxiv.org/pdf/2112.00405.pdf).

The corpus (used for named entity recognition pre-training) can be downloaded from [here](https://hkustconnect-my.sharepoint.com/:f:/g/personal/zliucr_connect_ust_hk/EnULFBaS3slImV5Of99-j_UBhnyvp0_Xarl_bSb4QCzvfw?e=MZMdPP). The description of each file is as follows:
- ```annotated_ner_data_train.txt``` Data for the NER pre-training
- ```augmented_ner_data_train.txt``` Data after conducting data balancing across entity categories (described in paper) on "annotated_ner_data_train.txt". We suggest to use this corpus version for the NER model pre-training.
- ```annotated_ner_data_dev.txt``` Data for the evaluation of the NER pre-training

If you use any resources included in this repository for your work, please kindly cite the following paper:
<pre>
@article{liu2021ner,
  title={NER-BERT: a pre-trained model for low-resource entity tagging},
  author={Liu, Zihan and Jiang, Feijun and Hu, Yuxiang and Shi, Chen and Fung, Pascale},
  journal={arXiv preprint arXiv:2112.00405},
  year={2021}
}
</pre>
