# AbstractiveSummarizationusingNMT
Automatic text summarization is the task of producing a concise and fluent summary while preserving key information content and overall meaning
There are broadly two different approaches that are used for text summarization:

Extractive Summarization
Abstractive Summarization


Extractive Summarization


The name gives away what this approach does. We identify the important sentences or phrases from the original text and extract only those from the text. Those extracted sentences would be our summary. 

Abstractive Summarization
We can build a Seq2Seq model on any problem which involves sequential information. This includes Sentiment classification, Neural Machine Translation, and Named Entity Recognition – some very common applications of sequential information.

Our objective is to build a text summarizer where the input is a long sequence of words (in a text body), and the output is a short summary (which is a sequence as well). So, we can model this as a Many-to-Many Seq2Seq problem.
