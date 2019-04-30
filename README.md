# opencog-qa
OpenCog-based language generator for Question Answering


1. Collect the data. The best way to do that is probably to use OpenSubtitles.org's API. (https://www.quora.com/Where-can-I-get-a-large-collection-of-movie-subtitles)
2. Extract grammatical knowledge from the data. Maybe identify questions and answers to create a more focused dataset?
3. Model ideas: 
    1. Learn the english language using general text and then specialize / do transfer learning for the structure of answers.
    2. Use one model to learn english and another to learn the structure of answers. Use the latter to guide the word choice of the former. (What about the context of the question?)
    3. 
    
Study:
- Sequence Models for text generation
- Question Answering models