# PubMedWordCloud
Articles titles mining in PubMed using Python script to find trending words and saving results in any given image background
```r{}
pubmed_word_cloud = PubMedWordCloud(stopwords_list="nltk_data")
pubmed_word_cloud.generate_pubmed_word_cloud(search_term = 'brain cancer',
                                             mask_image_path = 'brain.png',
                                             n_papers = 50, 
                                             Freq = 2,
                                             figsize=(18, 18))

```
