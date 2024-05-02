# MILDSum: A Novel Benchmark Dataset for Multilingual Summarization of Indian Legal Case Judgments

Paper Accepted at the **EMNLP 2023 Main Conference!** <a href="https://aclanthology.org/2023.emnlp-main.321/">[Paper]</a>

## The MILDSum Dataset 
<b> MILDSum </b> (**M**ultilingual **I**ndian **L**egal **D**ocument **Sum**marization) dataset is a collection of 3,122 Indian court judgments in English along with their summaries in both English and Hindi, drafted by legal practitioners.

A sample of <b> MILDSum </b> dataset can be found under the `Data/MILDSum_Samples` folder. For the full dataset, please contact to {debtanudatta04 [at] gmail [dot] com}.

#### Folder Structure
Each sample subdirectory contains 3 txt files -- <i>EN_Judgment.txt</i>, <i>EN_Summary.txt</i>, and <i>HI_Summary.txt</i>. Where <i>EN_Judgment.txt</i> contains the original case judgment. <i>EN_Summary.txt</i> and <i>HI_Summary.txt</i> contain corresponding English and Hindi summaries, respectively.

## Citation
If you use this dataset, please refer to the following paper:
```
@inproceedings{datta-etal-2023-mildsum,
    title = "{MILDS}um: A Novel Benchmark Dataset for Multilingual Summarization of {I}ndian Legal Case Judgments",
    author = "Datta, Debtanu  and
      Soni, Shubham  and
      Mukherjee, Rajdeep  and
      Ghosh, Saptarshi",
    editor = "Bouamor, Houda  and
      Pino, Juan  and
      Bali, Kalika",
    booktitle = "Proceedings of the 2023 Conference on Empirical Methods in Natural Language Processing",
    month = dec,
    year = "2023",
    address = "Singapore",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2023.emnlp-main.321",
    pages = "5291--5302",
    abstract = "Automatic summarization of legal case judgments is a practically important problem that has attracted substantial research efforts in many countries. In the context of the Indian judiciary, there is an additional complexity {--} Indian legal case judgments are mostly written in complex English, but a significant portion of India{'}s population lacks command of the English language. Hence, it is crucial to summarize the legal documents in Indian languages to ensure equitable access to justice. While prior research primarily focuses on summarizing legal case judgments in their source languages, this study presents a pioneering effort toward cross-lingual summarization of English legal documents into Hindi, the most frequently spoken Indian language. We construct the first high-quality legal corpus comprising of 3,122 case judgments from prominent Indian courts in English, along with their summaries in both English and Hindi, drafted by legal practitioners. We benchmark the performance of several diverse summarization approaches on our corpus and demonstrate the need for further research in cross-lingual summarization in the legal domain.",
}
```

## Contact
For any inquiries, feedback, or collaboration opportunities, please contact to {debtanudatta04 [at] gmail [dot] com}.
