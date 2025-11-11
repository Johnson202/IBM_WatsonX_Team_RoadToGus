# IBM_WatsonX_Team_RoadToGus

## Overview
IBM Granite-3.1-8B-Instruct model was chosen for optimal outputs in the personal finance domain (based on available foundational models, in terms of cost vs. risk).
Mistral Medium 3 model scored the highest on the basis of the FinQA metric, at 40 (relative to all other foundational models available in Prompt Lab in WatsonX). IBM Granite-3.1-8B-Instruct model scored only a 5 in terms of the FinQA metric, but due to its low cost and still decent performance in a client-facing setting or when used in regulated settings, Granite is the safer, more reliable pick.

##Dataset Sources
Personal_Finance_Dataset(.csv/.txt): https://www.kaggle.com/datasets/ramyapintchy/personal-finance-data
Budget(.csv/.txt): https://www.kaggle.com/datasets/bukolafatunde/personal-finance
fine-tuning data.json: 1) https://www.protective.com/learn/personal-finance-faqs 
                       2) https://www.investopedia.com/personal-finance-4427760 
                       3) https://www.fidfedsl.com/blog/financial-literacy-faq-your-top-questions-answered/ 
                       4) https://digitaldefynd.com/IQ/personal-finance-faqs/
