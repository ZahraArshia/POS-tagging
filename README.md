# POS tagging

POS Tagging (Parts of Speech Tagging) is a process to mark up the words in text format for a particular part of a speech based on its definition and context. It is responsible for text reading in a language and assigning some specific token (Parts of Speech) to each word. It is also called grammatical tagging.

![image](https://user-images.githubusercontent.com/78906545/164948168-cea6e682-c664-48a9-9030-0f9942436d3f.png)

# List of abbreviations
![image](https://user-images.githubusercontent.com/78906545/164948186-8fd29962-d11f-49b3-8395-3ee7d10633a7.png)

# Types of POS taggers
**1.Rule-Based POS Tagger:** For the words having ambiguous meaning, rule-based approach on the basis of contextual information is applied. It is done so by checking or analyzing the meaning of the preceding or the following word. Information is analyzed from the surrounding of the word or within itself. Therefore words are tagged by the grammatical rules of a particular language such as capitalization and punctuation. e.g., Brill’s tagger.

**2.Stochastic POS Tagger:** Different approaches such as frequency or probability are applied under this method. If a word is mostly tagged with a particular tag in training set then in the test sentence it is given that particular tag. The word tag is dependent not only on its own tag but also on the previous tag. This method is not always accurate. Another way is to calculate the probability of occurrence of a specific tag in a sentence. Thus the final tag is calculated by checking the highest probability of a word with a particular tag.
