# Learning Job Title Representation from Job Description Aggregation Network
The official implementation of ACL 2024 findings 

The [mycareersfuture.sg](https://github.com/WING-NUS/JD2Skills-BERT-XMLC/tree/main) is used as a training dataset. We concatenate the fields "Role & Responsibilities" and "Job Requriement" to represent the job description.



The evaluation dataset is taken from [ESCO-Job Normalization](https://github.com/jensjorisdecorte/JobBERT-evaluation-dataset) where the goal is to predict the standized version of each job title. Following the jobbert paper, we measure micro-average R@5,R@10 and MRR.


Our pre-trained job title representation model can be found on [https://huggingface.co/napatnicky/JDAN-mycareersfuture.sg](https://huggingface.co/napatnicky/JDAN-mycareersfuture.sg)
