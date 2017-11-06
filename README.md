# TFChatbot
Make Chatbot with TensorFlow sequence to sequence, model train on the [Cornell Movie Dialogue dataset](https://www.cs.cornell.edu/~cristian/Cornell_Movie-Dialogs_Corpus.html), the bot is able to hold a fun conversation.

Dependencies
============
* numpy
* scipy 
* six
* tensorflow (https://www.tensorflow.org/versions/r0.12/get_started/os_setup.html) (Important version 0.12)

Usage
===========

To train the bot, edit the `seq2seq.ini` file so that mode is set to train like so

`mode = train`

then run the code like so

``python execute.py``

To test the bot during or after training, edit the `seq2seq.ini` file so that mode is set to test like so

`mode = test`

then run the code like so

``python execute.py``


Credits
===========
Credit for the vast majority of code here goes to [suriyadeepan](https://github.com/suriyadeepan). I've merely created a wrapper to get people started. 

@Sirajology on [Youtube](https://youtu.be/SJDEOWLHYVo)
