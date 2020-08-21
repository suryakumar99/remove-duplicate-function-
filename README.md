# remove-duplicate-function-
def removeDuplicate():
    userInput = input().split(', ')
    uniqueWords = set()
    for word in userInput:
        if(word not in uniqueWords):
            uniqueWords.add(word)
    print(uniqueWords)
removeDuplicate()
