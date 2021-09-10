# Science-quiz
#Kids Friendly science Quiz#

print ('Welcome to my quiz')

playing = input ('Shall we begin? ')


if playing.lower() != 'yes':
    quit()

print('okay! Game is loading :)')

score = 0

answer = input ('What does DNA stand for? ')
if answer.lower() == 'deoxyribonucleic acid' :
    print ('correct')
    score += 1

else :
    print('incorrect')
    
playing = input ('Next Question ') 
if playing.lower() != 'yes':
    quit()

answer = input ('how many bones are in the human body? ')

if answer.lower() == '206' :
    print('correct')
    score += 1

else:
    print('Incorrect')

playing = input ('Next Question ') 
if playing.lower() != 'yes':
    quit()
answer = input ('Who discovered the concept of Gravity? ')
if answer.lower() == 'issac newton':
    print('correct')
    score += 1

else:
    print('Incorrect')

print ('you got '   +    str(score)   +    ' questions correct')
print ('you got '  +  str(score/3*100)  +
