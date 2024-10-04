meme_dict = {
            "CRINGE": "Garip ya da utandırıcı bir şey",
            "LOL": "Komik bir şeye verilen cevap",
            "ROFL": "Bir Şakaya Karşılık Cevap",
            "SHEESH": "onaylamamak",
            "CREEPY": "Korkunç",
            "AGGRO": "agresifleşmek",
            "NVM": "Boşver",
            "JK": "Şaka Yapıyorum",
            "POV": "Bakış Açısı"
            }
word = input("bir kelime yazın(Büyük Harflerle)")
if word in meme_dict.keys():
    print(meme_dict[word])
else:
    print("Böyle bir kelime sözlükte yok")
