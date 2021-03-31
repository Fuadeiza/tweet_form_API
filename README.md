1.  For the 'plagiarism checker' I'd use a sklearn library, most likely TFID vectorizer for tokenizing the texts and then use cosine_similarity for checking the percentage of plagiarism between the summarized text and the original text  OR better still I use spaCy NLP processing libray for similarity checker.

2. Use serializer validation to run the 'value(python_tip') against other tips in the DB, If there's any with % greater than 70%, a validationError would be thrown.

3.  Do API testing for the endpoints( status_code )

4. What does Endpoints for likes and Bookmark mean??