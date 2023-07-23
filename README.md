# Text-generation_model
The text-generation model using rnn-lstm algorthm deep learning is able to generate the text based on the related text input as a seed_text and then it generate the next text based on the input text.
the datasets which is used for the creating this model is a poem dataset which is available on the kaggle notebook.
the datasets is being preprocessed using tokenizer and others cleaning function which help this model to train effectively , before that the datasets should be in the lower case and also remove the punctation for getting better results.

This model uses 4-5 layers of lstm from input layer to the output including the two dense layers.
In this i used the loss function as categorical_crossentropy and a Adam optimizer;for the input text i used the 20 words and the next 21st word will be generate by this model(input text can by anything based on your choice).


It took around 900-1100 epochs for training this model with a accuracy of around 90%-93%,it can even get better results if we train with more epochs , but if we take too much epochs than the model will be overfitting and then result might get low.so based on the type of model building it should be adjusted based in that.
