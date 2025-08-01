
## Project Overview

This project aims to classify movie reviews as either positive or negative using the IMDB dataset. The dataset is preprocessed and tokenized, and the model is trained using an LSTM-based neural network.

   Input Sequence (100 words) <br>
         │ <br>
   ┌─────┴─────┐ <br>
   │ Embedding │  -> Converts words to dense vectors (32-dimensional) <br>
   └─────┬─────┘ <br>
         │ <br>
  ┌──────┴──────┐ <br>
  │   LSTM      │  -> LSTM with 32 units, returns sequences <br>
  └──────┬──────┘ <br>
         │ <br>
  ┌──────┴──────┐ <br>
  │   LSTM      │  -> LSTM with 32 units, final sequence output <br>
  └──────┬──────┘ <br>
         │ <br>
  ┌──────┴──────┐ <br>
  │  Dense (1)  │  -> Final output: Binary classification (positive/negative) <br>
  └─────────────┘ <br>
