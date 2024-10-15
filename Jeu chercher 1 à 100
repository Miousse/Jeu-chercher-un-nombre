import random
def alea():
    cible = random.randint(1,100)
    trouve = 7
    print('trouve un chiffre entre 1 a 100 en 7 fois')
    
    for i in range(trouve):
        devine = int(input(f'Tu es a {i + 1}, met ton nombre '))
        if devine < cible:
            print('Le nombre est plus grand que le tiens')
        elif devine > cible:
            print('Le nombre est plus petit que le tiens')
        else:
            print('Vous avez trouve')
            
            break
    else:
        print(f'Finie !!. Le nombre etait: {cible}')
