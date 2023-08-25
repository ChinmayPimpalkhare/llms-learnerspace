This is the readme file for the project. 


We are making use of the GPT-2/Bert transformer model. GPT-2 has upto 1.5 billion parameters, and is very goid at generating coherent and contextually relevant text. Bert has about 110 million parameters. 

We are also making use of the huggingface transformers models for that. In addition to that, we integrate Gradio with it since it allows us a nice interface to get outputs directly. 

The huggingface library of datasets allows us to get dataset easily without local installation. 

We shall be using the "Yelp Reviews Dataset". This dataset contains reviews of various kinds. It has both positive and negative reviews. It shall be helpful to get both kinds of sentiments into our dataset.

Tokenization is essentially splitting of long lines of texts into words called tokens. The tokenizer we have used is the "Bert-base-Cased" tokenizer. 

The pre-trained model which we are using is also the "Bert-base-cased" model. In a later stage we shall be using the GPT-2 model. We use the AutoModel currently. 

The evaluate library is used for the metric evaluation. 

We also make use of the Trainer module. 

At the end of 3 epochs, the model was able to achieve a humble accuracy of 59%!!! 

# Difficulties
Was learning using Gradio and implementing a transformer for the first time, so there was a bit of trouble there. The Gradio GUI was not working as expected. 
The Hugging Face documentation was quite helpful in trying to understand what I wanted to do. 
