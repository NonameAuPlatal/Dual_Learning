# Dual_Learning
This is a project that I did in my last internship. I have implemented it with small copora (50000 sentences) and I got good results. I am currently working on this, doing more experiments with large corpora (millions sentences) and gradually improving the clarity of the code. I hope that I can finish it soon. There is a lot of work whereas I am still busy at school. Thanks for your interests.

I suggest you using my new version implementation of Dual Learning which uses Q-value to estimate Policy Gradient.
To train model, you need to pretrain 2 language models (using code of dl4mt) and put them in models/LM and 2 translation models using old version of nematus provided in my Github (for warmstart) and put them in models/name_of_your_warmstart_directory/NMT.
 
