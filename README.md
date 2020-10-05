# jarvis-




def speak(audio):
       pass      #For now, we will write the conditions later.
       
       
       
       
       
       
       pip install pyttsx3
       
       pip install pypiwin32.
       
       
       
       
       
       
       
       
       
       
       
       
       
       
       
       
       
       
       import pyttsx3

engine = pyttsx3.init('sapi5')

voices= engine.getProperty('voices') #getting details of current voice

engine.setProperty('voice', voice[0].id)






















  try:
        print("Recognizing...")    
        query = r.recognize_google(audio, language='en-in') #Using google for voice recognition.
        print(f"User said: {query}\n")  #User query will be printed.

    except Exception as e:
        # print(e)    
        print("Say that again please...")   #Say that again will be printed in case of improper voice 
        return "None" #None string will be returned
    return query







