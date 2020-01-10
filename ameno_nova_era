#this program is for testing repository on github. Should must ask the forgiven lytics of the song Ameno by ERA.

def start():

    print('\nAmeno-Era\nSing with us(Write \"Dori me\" or \"Ameno\" when\nthe program forgets the lyrics.'
          'Remember:\nsentences start with uppercase).\n\n((Music))\n\n')

    print('(Omenare imperavi emulari\nAmeno\nOmenare imperavi emulari)\n')
def dori_me():
    print('Interimo adapare\nDori me\nAmeno ameno\nLatire latiremo\nDori me\n')

def ameno():
    print('Omenare imperavi\nAmeno\nDimere dimere\nMatiro matiremo\nAmeno\n')

def chorus():
    print('Ameno dore\nAmeno dori me\nAmeno dori me\n\nAmeno dom\nDori me reo\n'
      'Ameno dori me\nAmeno dori me\nDori me am\n')

####AQUI COMEÇA A MÚSICA####

start()
estrofe=1
end=False

while end==False:
    remember=input('')
    if remember!='Dori me' and remember!='Ameno':
        print('Wrong!!')
    while remember=='Dori me' or remember=='Ameno' and end==False:
        if remember=='Dori me' and estrofe==1:
            dori_me()
            estrofe += 1
            remember=input('')
        elif estrofe<1:
            print("Wrong!!\n")
            remember=input('')
        if remember=="Ameno" and estrofe==2:
            ameno()
            estrofe += 1
            end=True
        else:
            print("Wrong!!")

end=False

estrofe+=1

print('(Omenare imperavi emulari\nAmeno\nOmenare imperavi emulari)\n')

while end==False:
    remember=input('')
    if remember=='Ameno':
        chorus()
        end==True
    else:
        print("Wrong!!")

    end=True

