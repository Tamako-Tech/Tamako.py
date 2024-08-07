# Tamako.py
An easy to use and actually updated Python wrapper for the Tamako API.

## State of the project:
~~The wrapper is in constent development and will continue to be. Everything in the Tamako API.~~
This project is now discontinued, while it may still work it is not up to my (Leo's) current standard of development and the status of the Tamako API is unknown.

## How to install:
```py
Windows:
pip install Tamako.py
```
```py
Linux/MacOS:
pip install Tamako.py
```

## Getting Started
Using Tamako.py is quite simple, see the documentation for more details. Nearly all of the features included in this API wrapper work without any api keys. To use the ChatBot feature please take a look at the [Tamako documentation](https://tamako.tech/docs/api/chatapi).

## Quick example of the chatbot:

```py
chatbot = Tamako.chatbot(prvid='', svcid='', svcsecret='', name='', gender='', prefix='', dev='', userid='', message='')
print(chatbot)
```
where `prvid`, `svcid` and `svcsecret` are the Provision ID, Service ID & Service Secret respectively on the [SDC](https://devcenter.skyfallen.org/accounts/login)

## A quick example of printing a joke:

```py
import Tamako
from Tamako import Tamako

joke = Tamako.joke()
print(joke)
```

## A quick example of printing lyrics of a song:

```py
lyrics = Tamako.lyrics(song_name='Lucid Dreams')
print(lyrics)
```

## A quick example of printing facts of an animal:

```py
fact = Tamako.animal_fact(animal='cat')
print(fact)
```

## A quick example of printing the url of an image

```py
img = Tamako.image(animal='bird')
print(img)
```
