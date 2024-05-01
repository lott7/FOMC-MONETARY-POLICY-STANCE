# FOMC-MONETARY-POLICY-STANCE

### Label Interpretation
**(2) : Neutral**  
**(1) : Hawkish**  
**(0) : Dovish**  

# Introduction
Welcome to our repository for the final project of the MGT 6785 "QCF Practice" class! Here, we present the culmination of our efforts in utilizing Natural Language Processing (NLP) techniques to analyze the stance of FOMC (Federal Open Market Committee) data. Our aim is to predict whether the sentiment expressed in the data is Neutral, Hawkish, or Dovish, as per the labels defined above.

According to Shah, Paturi, and Chava (2023), monetary policy pronouncements by the Federal Open Market Committee (FOMC) significantly impact financial market returns. They constructed a comprehensive dataset of FOMC speeches, meeting minutes, and press conference transcripts to analyze the influence of monetary policy on financial markets. The study introduces a novel task of hawkish-dovish classification and evaluates various pre-trained language models on this dataset. Their findings suggest that the constructed measure of monetary policy stance, using the RoBERTa-large model, is instrumental in understanding the effects of FOMC document releases on treasury markets, stock markets, and macroeconomic indicators.

Given that the research done by Shah, Paturi, and Chava (2023) is really at the core of the intersection of GenAI and financial markets, we wanted to take their research as our basis. After an initial discussion with Prof. Dr. Chava, we agreed to make our project a standalone expansion of their previous work. That being said, the idea was to annotate the data from the years 2023 to 2024 and use the first year as the training set for fine-tuning purposes, then test the accuracy of our model on the already available data from 2024. Since the RoBERTa-large model performed the best in the paper by Shah, Paturi, and Chava (2023), we wanted to focus on that model from the beginning to the end.

For further exploration, you can refer to:
- Shah, A., Paturi, S., & Chava, S. (2023). Trillion Dollar Words: A New Financial Dataset, Task & Market Analysis. Retrieved from https://doi.org/10.48550/arXiv.2305.07972
- FOMC-Hawkish-Dovish Github: [https://github.com/gtfintechlab/fomc-hawkish-dovish](https://github.com/gtfintechlab/fomc-hawkish-dovish)
- Hugging Face: [https://huggingface.co/gtfintechlab/FOMC-RoBERTa](https://huggingface.co/gtfintechlab/FOMC-RoBERTa)
- Gorodnichenko, Yuriy, Tho Pham, and Oleksandr Talavera. The Voice of Monetary Policy. Working Paper 28592. March 2021. Retrieved from [https://www.nber.org/papers/w28592](https://www.nber.org/papers/w28592)





