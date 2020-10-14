# google-translater
from googletrans import Translator
sentence = input("lets type =")
translator = Translator()
translated = translator.translate(sentence,src='en',dest='es')
print(translated.text)
