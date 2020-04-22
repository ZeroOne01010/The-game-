# The-game-
Simple guessing game 
print('welcome to the game\n') 
gamePrompt = 'enter a value between 0.0 and 1.0\n' 
score = float(input(gamePrompt))

if score > 1.0:
    print('Too high!')
elif score < 0.0:
    print('Too low!')
elif score >= 0.9:
    print('A')
elif score >= 0.8:
    print('B')
elif score >= 0.7:
    print('C')
elif score >= 0.6:
    print('D')
elif score < 0.6:
    print('F')
