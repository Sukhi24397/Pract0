EXPERIMENT 16:

Aim:
To study and implement various Natural Language Processing (NLP) techniques in Python using the NLTK library, 
including tokenization, stop word removal, stemming, lemmatization, part-of-speech tagging, and frequency distribution.

Theory :

Natural Language Processing (NLP) is a subfield of Artificial Intelligence (AI) that focuses on enabling computers to understand,
interpret, and generate human language in a meaningful way. Human language is complex, ambiguous, and highly contextual, which makes NLP a challenging area of study. The development of NLP techniques allows machines to process large amounts of textual data efficiently and extract useful information from it.

In this experiment, Python along with the NLTK (Natural Language Toolkit) library is used to perform various fundamental NLP operations. These operations form the basis of more advanced applications such as machine translation, sentiment analysis, speech recognition, and chatbots.

🔹 1. Text Preprocessing

Text preprocessing is the first and most important step in NLP. Raw text data often contains noise such as punctuation, special characters, and irrelevant words. Preprocessing helps clean and standardize the text so that it can be analyzed effectively.

🔹 2. Tokenization

Tokenization is the process of breaking down a large text into smaller units called tokens. These tokens can be words, sentences, or characters.

Word Tokenization: Splitting text into individual words
Sentence Tokenization: Dividing text into sentences

This step is essential because most NLP tasks operate on tokens rather than raw text.

🔹 3. Stop Word Removal

Stop words are commonly used words such as is, the, in, on, and, etc., which do not carry significant meaning in text analysis. Removing stop words helps:

Reduce the size of the dataset
Improve processing efficiency
Focus on meaningful words

NLTK provides a predefined list of stop words for multiple languages.

🔹 4. Stemming

Stemming is the process of reducing words to their root or base form by removing suffixes. It uses simple heuristic rules.

Examples:

running → run
happiness → happi

Although stemming is fast, it may not always produce meaningful words.

🔹 5. Lemmatization

Lemmatization improves upon stemming by converting words into their correct base or dictionary form (lemma). It considers the context and part of speech of the word.

Examples:

better → good
running → run

Lemmatization produces more accurate and meaningful results compared to stemming.

🔹 6. Part-of-Speech (POS) Tagging

POS tagging involves identifying the grammatical role of each word in a sentence, such as noun, verb, adjective, etc.

Example:

“The cat is running”
The → Determiner
cat → Noun
running → Verb

This helps in understanding sentence structure and meaning.

🔹 7. Frequency Distribution

Frequency distribution is used to count how often each word appears in a text. It is useful for:

Identifying important words
Keyword extraction
Text summarization

It can also be visualized using graphs or charts.

🔹 8. Importance of NLTK

NLTK is a powerful Python library designed for working with human language data. It provides:

Easy-to-use APIs for NLP tasks
Large collections of text datasets
Tools for classification, parsing, and tagging

It is widely used in academic and research environments for learning NLP concepts.

🔹 9. Applications of NLP

The techniques demonstrated in this experiment are widely used in real-world applications such as:

Chatbots and virtual assistants
Sentiment analysis (e.g., product reviews)
Machine translation (e.g., Google Translate)
Text summarization
Spam detection in emails

Conclusion:
The experiment successfully demonstrates how basic NLP techniques can be implemented using Python and NLTK. It shows how raw text can be processed and transformed into a structured format for analysis.
These techniques form the foundation for advanced applications like text classification, sentiment analysis, and chatbots.
