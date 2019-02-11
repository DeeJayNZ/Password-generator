# Password-generator
generates a random password

#passwordgenerator
def main():
    from random import randint
    pass_strength = int(input("how many characters would yoiu like in your password? "))
    alphabet = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','1','2','3','4','5','6','7','8','9','0','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','-','_','+','=','/','?','!','@','#']
    count = pass_strength
    while count>0:
        password = password + alphabet[randint(0,69)]
    print (password)
main()



#69 in alphabet
