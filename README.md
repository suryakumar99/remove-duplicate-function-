# remove-duplicate-function-
def removeDuplicate():
    userInput = input("enter the word to remove duplicates :").split(', ')
    Withoutduplicate = set()
    for word in userInput:
        if(word not in withoutduplicate):
            Withoutduplicate.add(word)
    print(withoutduplicate)
removeDuplicate()
