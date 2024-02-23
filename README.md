# Friday-Project-4
AI generated code for all previous Friday projects in DS-3850

def madlib():
    # Welcome message
    print("Welcome to MadLibs!")
    
    # Asking for input
    adjective1 = input("Enter an adjective: ")
    noun1 = input("Enter a plural noun: ")
    verb1 = input("Enter a past tense verb: ")
    adverb1 = input("Enter an adverb: ")
    adjective2 = input("Enter another adjective: ")
    noun2 = input("Enter a noun: ")
    verb2 = input("Enter a verb: ")
    adjective3 = input("Enter another adjective: ")
    adverb2 = input("Enter another adverb: ")
    verb3 = input("Enter another verb ending in 'ing': ")
    noun3 = input("Enter another plural noun: ")
    
    # Printing the story with user input
    print("\nHere's your MadLib:")
    print("Today, I went to the zoo. I saw a", adjective1, "bunch of", noun1 + ".")
    print("One", noun1, "in particular", verb1, adverb1, "while it was", adjective2 + ".")
    print("It made me", verb2, "a little, but it was still", adjective3 + ".")
    print("Later, I saw a", noun2, "that started", verb3, adverb2 + ".")
    print("I think I'll stick to the", noun3, "next time!")

if __name__ == "__main__":
    madlib()
    