This repository provides the evaluation datasets used in our paper ["Time-Considerable Dialogue Models via Reranking by Time Dependency"](https://pages.github.com/) (EMNLP Findings 2023).

In the datasets, tweets are utilized as utterances. However, in compliance with Twitter API policies, only the tweet IDs are listed in the datasets.
Note that the dataset consists tweet IDs that are identifiable at the present time.

This repository provides two datasets:
1. nuta_dataset.tsv: The NUTA dataset constructed in Section 3.1.
   - tweet_id: utterance
   - response: response to the utterance (manually created)
   - nuta_category: categorization of responses (1 corresponds to AN, 2 to TN, 3 to TU, and 4 to AU)
   - time: spoken time (hour)
1. evaluation_dataset.tsv: The evaluation dataset constructed in Section 5.2.
   - tweet_id: utterance
   - time: spoken time (hour)

For further details and usage instructions regarding the datasets, please refer to our paper.