# remove-duplicate-function-
def removeDuplicate():
    # input format: word1, word2, word3...
    userInput = input().split(', ')
    uniqueWords = set()
    for word in userInput:
        if(word not in uniqueWords):
            uniqueWords.add(word)
    print(uniqueWords)
removeDuplicate()
