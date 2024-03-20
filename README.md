# Summary
Using a trained model to classify restaurant customer service domain user text input based on several trained text intent classes and then provide a suitable reply as an output, in a Juypter Notebook environment only (code cell terminal). 
 
This is essentially achieved by using spaCy NLP library to first perform preprocessing on text training data and thereafter feeding it into distilBERT pretrained transformers model for it to undergo PyTorch machine learning. 

But the text training data can easily be swapped to include other text intent classess in other domains or expanded to include much more new text intent classess. 

Text training data can even include non English languages if the models used can parse it correctly.  

# Possible Future Work (Musings)

Provide several possible reply options to incoming messages in messaging apps based on your previous messaging writing style.

Currently no popular apps offer any feature that can allow possible replies for you to choose from to reply to incoming chats, based on your typical style of messaging.

An app that can provide possible responses for the end user to click and choose before sending, while taking into account context of previous conversations in the chat history will no doubt be very useful.
Since text messaging can be very short at times, the scope of the app should naturally be limited to longer character length (e.g. 10 of more English characters) incoming messages. 

However, sufficient text of a particular class needs to be present & labelled to undergo training for some time and requires significant computational power from somewhere (local/cloud).  

*Refactoring my code for increased understanding for beginners or adding more comments may be done someday...

# Flowchart 
The essential overview of my entire chatbot program 

<img width="877" alt="Flowchart" src="https://github.com/MSHI005/Chatbot-NO-GUI/assets/159223357/22c93734-6709-441e-a4e9-c2d74f8bdb8f">



# Results
Sample conversations for a particular training iteration only. 

Results may not always be exactly reproducible.  

For now, there is only a single fixed response for each of the text intent classes, but you can easily add more, and then include in the chatbot logic to randomly choose a particular response.   


Successfull

<img width="392" alt="Success" src="https://github.com/MSHI005/Chatbot-NO-GUI/assets/159223357/1490cef6-cd16-4bb0-b3da-86c717583719">

<img width="676" alt="Success_2" src="https://github.com/MSHI005/Chatbot-NO-GUI/assets/159223357/90463c51-aaac-49c4-bd5c-6d7ac07689cb">


Unsuccessful (Fail)

<img width="404" alt="Fail" src="https://github.com/MSHI005/Chatbot-NO-GUI/assets/159223357/125b1b02-f505-43f3-b221-502b8fdccc6a">


<img width="517" alt="Fail_2" src="https://github.com/MSHI005/Chatbot-NO-GUI/assets/159223357/77f16d8f-ca38-41f4-baaf-fa96084ed44d">

# NOTICE
The Juypter Notebook was executed and adapted to the Google Colab runtime environment before uploading. 

Hence, the code cell outputs may look unideal printed out in other environments, but it looks fine by default in Google Colab.

And for now, this project will mainly be further continued locally or in Google Colab per se without source control using Git and uploaded to Github. 

The original image_dataset.zip was not backed up and cannot be recovered, but any small image dataset zipped file with the specified file directory structure can work as well.   
Much more information can be found inside the notebook so that this README.md file can be kept concise.
