word = ["zero", "one", "two", "three","four", "five", "six", "seven", "eight", "nine"]
def printWordsWithoutIfSwitch(number):
    digits = []
    dc = 0
    while True:
        digits.append(number%10)
        number = number/10
        dc = dc + 1
        if number == 0:
            break
    for i in range(dc-1, -1, -1):
        print word[digits[i]],
    
if __name__ == '__main__':
    printWordsWithoutIfSwitch(350530)
