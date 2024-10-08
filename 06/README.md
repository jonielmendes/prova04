# Questão 6 - Substituição

Em uma cifra de substituição, nós "criptografamos" (ou seja, ocultamos de forma reversível) uma mensagem, substituindo cada letra por outra letra. Para fazer isso, nós usamos uma chave: neste caso, um mapeamento de cada uma das letras do alfabeto à letra à qual ela deve corresponder quando criptografamos. Para "descriptografar" a mensagem, o receptor da mensagem precisará saber a chave, para que ele possa reverter o processo: traduzindo o texto criptografado (chamado geralmente de texto cifrado) de volta para a mensagem original (chamada geralmente de texto claro).

Uma chave, por exemplo, pode ser a string NQXPOMAFTRHLZGECYJIUWSKDVB. Esta chave de 26 caracteres significa que A (a primeira letra do alfabeto) deve ser convertida em N (o primeiro caractere da chave), B (a segunda letra do alfabeto) deve ser convertida em Q (o segundo caractere da chave) e assim por diante.

Uma mensagem como HELLO, então, seria criptografada como FOLLE, substituindo cada uma das letras de acordo com o mapeamento determinado pela chave.

# Entrada:
Chave: YTNSHKVEFXRBAUQZCLWDMIPGJO<br>
Palavra: Hello!<br>

# Saida:
Palavra Normal: Hello!<br>
Palavra Criptografada: Ehbbq!
