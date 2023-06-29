# MyChatBot
This is an exceptional ChatBot that has been created using 'DialoGPT' model. It tries to answer all your queries with appropriate answers!

#Installation and SetUp
[Install Python] https://www.dataquest.io/blog/installing-python-on-mac/

[Install pip] https://phoenixnap.com/kb/install-pip-mac

If you already have Python & pip installed then you can check their version in the terminal or command line tools

```
python3 --version
```

```
pip --version
```

## Installing Flask
This is an important step before we create the project
In your terminal run the requirements.txt file using this pip

```
pip install -r requirements.txt
```


## Running MyChatBot Application in Terminal

```
cd into your directory
```

```
python app.py
```



## What are we creating!

I have build a chatbot that can carry out conversations with users using natural language processing.

I've used "Microsoft DialoGPT", a pre-trained language model that can generate human-like responses to given prompts. It is with Flask, a popular Python web framework, to create a web application that can communicate with users via a chat interface.

For the frontend of our application, I've made use of  HTML, CSS, and JavaScript which will create a visually appealing and interactive chat interface. Additionally, jQuery is used to handle the HTTP requests that are made to the backend server.

Finally, I've created a fully functional chatbot that can engage in conversations with users with the techstack involving Microsoft DialoGPT, Flask, and web development technologies such as HTML, CSS, and JavaScript.

# ChatBot Link
The Chatbot is constructed using the Microsoft/DialoGPT-medium model.

```
https://huggingface.co/microsoft/DialoGPT-medium
```

# User-Html

```
var userHtml = '<div class="d-flex justify-content-end mb-4"><div class="msg_cotainer_send">' + user_input + '<span class="msg_time_send">'+ time + 
    '</span></div><div class="img_cont_msg"><img src="https://i.ibb.co/d5b84Xw/Untitled-design.png" class="rounded-circle user_img_msg"></div></div>';
```

# Bot-HTML

```
var botHtml = '<div class="d-flex justify-content-start mb-4"><div class="img_cont_msg"><img src="https://i.ibb.co/fSNP7Rz/icons8-chatgpt-512.png" class="rounded-circle user_img_msg"></div><div class="msg_cotainer">' + bot_response + '<span class="msg_time">' + time + '</span></div></div>';
```
