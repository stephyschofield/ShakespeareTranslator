# Shakespearean Translator
# Stephanie Schofield
# September 23, 2018
#
# Simple Shakespearean to Modern English dictionary. Prints translation when given user input of Shakespearean word.
# Words and definitions from >>> reference.yourdictionary.com/translation/shakespeare-translator.html

def shakespeare_word():
    s_word = input("Hello! Welcome to the Shakespeare to Modern English Translator!\nWhat word would you like to translate?  ")
    s_word = s_word.lower()
    return s_word

def translate(needs_trans):
    shakespeare_dict = {"abhor": "to reject, disdain", "absolute": "perfect", "addiction": "tendency, proneness",
                        "balk": "to hesitate or dispute", "brave": "handsome", "character": "letter, word",
                        "coil": "distress, trouble", "couch": "to go to sleep", "cousin": "friend",
                        "cunning": "clever, sharp", "delation": "accusation", "deserving": "reward",
                        "draw": "to bring near, call to", "egal": "equal", "emboss": "to track with the intent to kill",
                        "expedience": "quick", "fancy": "to desire", "fear": "to scare, frighten",
                        "front": "to oppose or object", "gast": "scared", "grave": "to bury", "heavy": "sad or painful",
                        "honest": "pure", "inherit": "given", "intpinse": "impossible to untangle", "judicious":
                        "fair, equitable", "knap": "to hit or strike", "knave": "a young boy or servant", "land": "yard",
                        "lapsed": "shocked, overcome", "mad": "crazy, wild", "mate": "to confuse or to match",
                        "note": "a bill or list, to take note of", "o'er-rauhot": "overcome",
                        "o-er wrought": "overcome", "ought": "privy to, promised", "painful": "difficult",
                        "pall": "to wrap", "particoat": "to cover in colorful fabric", "perpend": "to think of or consider",
                        "prithee": "please, excuse me", "quaint": "beautiful, ornate", "quake": "to shake or tremble",
                        "quicken": "to bring to life", "rapture": "a fit, ecstasy", "retire": "to go to bed",
                        "ravin": "likely to destroy", "respect": "condsideration", "shrift": "to admit",
                        "simular": "counterfeit", "still": "forever", "subscription": "obedience",
                        "take": "to enthrall or overtake","tax": "blame", "testy": "worrisome", "thee": "you",
                        "thine": "yours", "thou": "you", "thy": "your", "trigon": "a triangle", "undergo": "to take on",
                        "unpregnant": "idiotic", "usance": "usage", "vile": "disgusting", "vindicative": "vengeful",
                        "wall-eyed": "wide-eyed, angry", "want": "to be unprepared", "young": "recent", "zany": "idiotic"}
        
    if needs_trans in shakespeare_dict:
        translated = shakespeare_dict.get(needs_trans)
        print()                                         # formatting
        print("Translation:", translated)
        r_try_again = input("Would you like to translate another word?  ")
        r_try_again = r_try_again.lower()
        if r_try_again == "yes":
            print()
            main()
    else:
        w_try_again = input("Unknown Shakespearean word. Try again?  ")
        w_try_again = w_try_again.lower()
        if w_try_again == "yes":
            print()
            main()
        
def main():
    needs_trans = shakespeare_word()
    translate(needs_trans)

main()
