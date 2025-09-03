# working-with-texts-in-LLMs
This is the basic code to convert raw text data into tokens for training purposes of a LLM. In this series I'll encode and process the book #Harry Potter ann the Sorcerers Stone.

I started with an outdated method and then progress toward modern tokenization known as #Byte Pair Enoding. This encoding method is also used in GPT-2 and GPT-3 architectures.

After this I am moving to the core part of the LLM's working which is predicting one word at a time and why LLM's are autoregressive models. We code how LLM predict next word using input-target pairs and get insights into dataset and dataloader of pytorch.

Now we encoding the byte pairs into a vector representation of 300 dimension using word-2-vecgoogle-300 library. This library is used to cpture the semantic meaning in the sentences. We know that CV models work very well because alongwith the pixels information, ot also capture the semantic relationship among the different features of the images. 

Now we also know that words in the sentences are in the some particular order, so along with the semantic meaning it is also important to capturing the order in the sentences. To do so we use positional encoding that is giving different vector value to different words based on their relative position in the words. It is of two type one is absolute positional encoding and other is relative positional encoding. If we work with small sentences we use absolute else relative. In GPT-2 architectiure we


