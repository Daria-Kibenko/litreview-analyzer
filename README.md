# Analyzing the tonality of book reviews

### Importance of Sentiment Analysis in Book Reviews

Sentiment analysis of book reviews plays a key role in understanding readers' emotional responses. It can be used to:

- Improve book recommendation systems.
- Help authors and publishers analyze reader feedback.
- Summarize and filter reviews for future readers.

### Personal Motivation and Challenges

In the past, I attempted to implement sentiment analysis on book reviews, but the validation accuracy barely reached 50%, often falling well below. 

In this project, I achieved **60% accuracy** on the validation set, which I consider a personal success. This task is especially challenging due to several reasons:

- **Complex language**: Book reviews often include mixed or ambiguous emotions in a single text.
- **Subtle sentiment**: Readers use metaphors, sarcasm, or abstract expressions that are difficult for models to interpret.
- **Class imbalance**: Some sentiment categories are underrepresented.
- **Limited resources**: Russian-language datasets and pre-trained models for book reviews are rare.

### Data Collection Limitations

Another challenge was data accessibility. Many popular online platforms for reading or selling books do not allow access to reviews via API. According to publicly available information, such access is often restricted to book authors and official partners.

Because of this, most users are left with two options:

- Use publicly available datasets (which may not match their needs).
- Collect and label data manually — which is the approach I used in this project.

Manual data collection and annotation required a lot of time and effort to ensure data quality and balance.
