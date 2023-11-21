# UD-MULTIGENRE
A dataset of instance-level text genre annotations from the paper:

**"UD-MULTIGENRE - a UD-based dataset of instance-level genre annotations"** (Danilova, V., Stymne, S., to be published at The Workshop on Multilingual Representations Learning, EMNLP 2023)



It is based on the data from the [Universal Dependencies](https://universaldependencies.org/) treebanks. It currently covers 17 text genres in 38 languages. The total size of the dataset (training and development) in tokens is 11096.9k, and in sentences - 657.4k. In addition, the test set currently includes data from 17 treebanks for five genres and 14 low-resource languages (119k tokens and 7.2k sentences).

The dataset enables new research as well as re-evaluation and a deeper understanding of prior research on genre-based data selection for cross-lingual dependency parsing. In addition, it is highly relevant for the research direction that investigates cross-lingual genre representation and classification.

## Genre selection criteria

| Genre            | In UD        | Criteria                                                                                                      |
|------------------|--------------|----------------------------------------------------------------------------------------------------------------|
| academic         | ✔            | Scientific articles and reports from different fields (medicine, oil and gas, humanities, computer science), and popular science articles |
| blog             | ✔            | Texts proceeding from blogging platforms like WordPress                                                        |
| email            | ✔            | Email messages                                                                                                |
| fiction          | ✔            | Fiction novels, stories, fairy tales. Documentation and patterns tend to include author or story names         |
| guide            |              | Wikihow, travel guides, instructions                                                                          |
| interviews       |              | Prepared interviews with celebrities, politicians, and businessmen                                            |
| learner\_essays  | ✔            | Essays of language learners on different topics that tend to contain grammar errors                            |
| legal            | ✔            | Legal and administrative texts, including texts from governmental websites                                     |
| news             | ✔            | Mainstream daily (online) news, Wikinews. We stick to short articles and exclude long-read newspaper articles since they often belong to popular science |
| nonfiction\_prose |            | Documentary prose, biographies, autobiographical narratives, memoirs, essays                                   |
| parliament       |              | Transcriptions of parliamentary speeches and debates                                                           |
| QA               |              | Data from Question Answering competitions                                                                     |
| reviews          | ✔            | Messages containing reviews and opinions                                                                      |
| social           | ✔            | Informal social media posts and discussions (e.g., Twitter, Telegram, Reddit, forum messages, and comments, etc.) |
| spoken           | ✔            | Transcriptions of spontaneous spoken speech: monologues and conversations                                     |
| textbook         |              | Educational literature, textbooks                                                                              |
| wiki             | ✔            | Main Wikipedia articles. Wikihow, Wikinews, Wikitravel, and Wikianswers are not considered in this category    |

