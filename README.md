dic1={
    "food":{
        "idoma": "nyam",
         "tiv": "mnger",
        "hausa": "abinci",
        "igbo": "nri",
        "italian": "cibo",
    }
}
    
dic2 ={
     "clothes":{
     "idoma":"abo",
     "tiv":"abo",
     "hausa":"tufafi",
     "igbo":"uwe",
     "italians":"vesiti",
    }
}

dic3 ={
    "money" :{
         "idoma":"ishima",
         "tiv":"kudi",
         "hausa":"kudi",
         "igbo":"ego",
         "italians":"denaro",
    }
}
dic4 ={
    "read":{
        "idoma" :"ka",
        "tiv":"kor",
        "hausa":"karanta",
        "igbo":"guo",
        "italians":"leggere"
       
    }
}
dic5={
     "family":{
         "idoma":"ufia",
         "tiv":"ityo",
         "hausa":"iyali",
         "italians":"famigilla",
     }
}

def word():
    word_input = input("Write a word: ")
    language = input("Pick a language: ")
if word=="food":
        dictionary=dic1["food"]
elif word =="clothes":
        dictionary=dic2["clothes"]
elif word =="money":
        dictionary=dic3["money"]
elif word =="read":
        dictionary=dic4["read"]
elif word =="family":
        dictionary=dic5["family"]
    else:
        print("word not available ")
        if language in dictionary:
        print(dictionary[language])
    else:
        print("Language not available")