print('HEY WELCOME!')
print('TO Tic Tac Toe Game')

list_of_game_pattern=[[" "," "," ",'|'," "," "," ",'|'," "," "," " ],["_","_","_","|","_","_","_","|","_","_","_"],[" "," "," ",'|'," "," "," ",'|'," "," "," " ],["_","_","_","|","_","_","_","|","_","_","_"],[" "," "," ",'|'," "," "," ",'|'," "," "," " ],[" "," "," ",'|'," "," "," ",'|'," "," "," " ]]
def playing(symbol):
	for item1 in list_of_game_pattern:
		for item2 in item1:
			print(item2,end='')
		print(' ')
print('enter your names')
name1=input()
name2=input()
print('What do you want to choose x or o:')
user=input()
if user=='x':
	player1='X'
	player2='O'
else:
	player2='X'
	player1='O'

print('Lets start the game by player who chooses X or O:')

def game():
	for loop in range(1,10):
		
		if loop%2==0:
			symbol=player2	
			name='x'
			print(f'{name1} turn:')	
		else:
			symbol=player1	
			name='O'
			print(f'{name2} turn:')
		userinput=int(input())
		if userinput==1:
			list_of_game_pattern[0][1]=symbol
			playing(name)

		elif userinput==2:
			list_of_game_pattern[0][5]=symbol
			playing(name)
			
		elif userinput==3:
			list_of_game_pattern[0][8]=symbol
			playing(name)
			
		elif userinput==4:
			list_of_game_pattern[2][1]=symbol
			playing(name)
			
		elif userinput==5:
			list_of_game_pattern[2][5]=symbol
			playing(name)
			
		elif userinput==6:
			list_of_game_pattern[2][8]=symbol
			playing(name)
			
		elif userinput==7:
			list_of_game_pattern[4][1]=symbol
			playing(name)
			
		elif userinput==8:
			list_of_game_pattern[4][5]=symbol
			playing(name)
			
		elif userinput==9:
			list_of_game_pattern[4][8]=symbol
			playing(name)

		if list_of_game_pattern[0][1]=='X' and list_of_game_pattern[0][5]=='X' and list_of_game_pattern[0][8]=='X':
			print("Match ends")
			break

		if list_of_game_pattern[0][1]=='O' and list_of_game_pattern[0][5]=='O' and list_of_game_pattern[0][8]=='O':
			print("Match ends")
			break
		if list_of_game_pattern[2][1]=='X' and list_of_game_pattern[2][5]=='X' and list_of_game_pattern[2][8]=='X':
			print("Match ends")
			break	

		if list_of_game_pattern[2][1]=='O' and list_of_game_pattern[2][5]=='O' and list_of_game_pattern[2][8]=='O':
			print("Match ends")
			break

		if list_of_game_pattern[4][1]=='X' and list_of_game_pattern[4][5]=='X' and list_of_game_pattern[4][8]=='X':
			print("Match ends")
			break	

		if list_of_game_pattern[4][1]=='O' and list_of_game_pattern[4][5]=='O' and list_of_game_pattern[4][8]=='O':
			print("Match ends")
			break
		if list_of_game_pattern[0][1]=='X' and list_of_game_pattern[2][5]=='X' and list_of_game_pattern[4][8]=='X':
			print("Match ends")
			break	

		if list_of_game_pattern[0][1]=='O' and list_of_game_pattern[2][5]=='O' and list_of_game_pattern[4][8]=='O':
			print("Match ends")
			break

		if list_of_game_pattern[4][1]=='X' and list_of_game_pattern[2][5]=='X' and list_of_game_pattern[0][8]=='X':
			print("Match ends")
			break	

		if list_of_game_pattern[4][1]=='O' and list_of_game_pattern[2][5]=='O' and list_of_game_pattern[0][8]=='O':
			print("Match ends")
			break

		if list_of_game_pattern[0][1]=='X' and list_of_game_pattern[2][1]=='X' and list_of_game_pattern[4][1]=='X':
			print("Match ends")
			break	

		if list_of_game_pattern[0][1]=='O' and list_of_game_pattern[2][1]=='O' and list_of_game_pattern[4][1]=='O':
			print("Match ends")
			break

		if list_of_game_pattern[0][5]=='X' and list_of_game_pattern[2][5]=='X' and list_of_game_pattern[4][5]=='X':
			print("Match ends")
			break	

		if list_of_game_pattern[0][5]=='O' and list_of_game_pattern[2][5]=='O' and list_of_game_pattern[4][5]=='O':
			print("Match ends")
			break
		if list_of_game_pattern[0][8]=='X' and list_of_game_pattern[2][8]=='X' and list_of_game_pattern[4][8]=='X':
			print("Match ends")
			break	

		if list_of_game_pattern[0][8]=='O' and list_of_game_pattern[2][8]=='O' and list_of_game_pattern[4][8]=='O':
			print("Match ends")
			break
game()

print('Do you want to play again ')
print('if yess press:1')
print('if no press:0')
play_again=int(input())
while play_again:
	list_of_game_pattern=[[" "," "," ",'|'," "," "," ",'|'," "," "," " ],["_","_","_","|","_","_","_","|","_","_","_"],[" "," "," ",'|'," "," "," ",'|'," "," "," " ],["_","_","_","|","_","_","_","|","_","_","_"],[" "," "," ",'|'," "," "," ",'|'," "," "," " ],[" "," "," ",'|'," "," "," ",'|'," "," "," " ]]
	game()
else:
	print('by by')
