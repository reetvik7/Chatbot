#CHATBOT
A generative ChatBot created using sequence-to-sequence model consists of two recurrent neural networks (RNNs): an encoder that processes the input and a decoder that generates the output.It does not have any specific dataset and can be trained on any dataset.Its not similar to other ChatBots which are hard coded for certain type of questions infact what this chatbot does is that it can understand the context of the user and hence respond accordingly.

Instructions to run:

There are three steps involved in running the chatbot:

To train the bot
1.Open the file "seq2seq.ini".
2.Set 'mode = train'.
3.Run the file execute.py using the code "python execute.py".

To test the bot after training
1.Open the file "seq2seq.ini".
2.Set 'mode = test'.
3.Run the file execute.py using the code "python execute.py".

Finally to launch the chatbot in serve mode run "host.pyw" file.
