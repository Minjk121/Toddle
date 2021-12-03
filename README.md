# Too-distracted-didn't-listen-enough (Toddle)
### Google x Break Through AI project
Toddle is a ml project that creates notes from audio lecture file.

#### AWS SDK
AWS Transcribe SDK was used to convert audio lecture files (mp3/mp4) to text files.
The audio file was first uploaded to AWS S3 bucket, and its uri link was used for using transcribe_file function.

#### Gensim
Gensim is a Python ibrary for topic modelling, document indexing and similarity retrieval with large corpora.
Its keywords and summerizer function were used to extract keywords and summerize the transcription.
More information can be found here: https://radimrehurek.com/gensim/

### Original team repository 
The original repository can be found here: https://github.com/sahanan13/toddle
