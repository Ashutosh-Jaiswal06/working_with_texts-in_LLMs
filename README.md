# working-with-texts-in-LLMs
This is the basic code to convert raw text data into tokens for training purposes. 

I started with an outdated method and then progress toward modern tokenization known as #Byte Pair Enoding. This encoding method is also used in GPT-2 and GPT-3 architectures.

After this I am moving to the core part of the LLM's working which is predicting one word at a time and why LLM's are autoregressive models. We code how LLM predict next word using input-target pairs and get insights into dataset and dataloader of pytorch.

Now we encoding the byte pairs into a vector representation of 300 dimension using word-2-vecgoogle-300 library. This library is used to cpture the semantic meaning in the sentences. We know that CV models work very well because alongwith the pixels information, ot also capture the semantic relationship among the different features of the images. 


