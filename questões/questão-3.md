# Observe o trecho de código abaixo: 
# int INDICE = 12, SOMA = 0, K = 1; enquanto K < INDICE faça { K = K + 1; SOMA = SOMA + K; } imprimir(SOMA);

O programa armazena valores na variável SOMA, e realiza um incremento de 1 à variável K (inicialmente com valor = 1), 
e realiza um loop até que K seja igual a 12. Quando k é gual a 12, o loop irá parar, ou seja, haverá um total de 11 
interações. 

Em cada interação, o valor SOMA, inicialmente igual a 0, realiza a adição do valor que está armazenado em K. Isso implica
numa soma diferente a cada interação do loop. 

Na primeira interação => SOMA = 0 + 2
Na segunda interação => SOMA = 2 + 3

No fim das interações, SOMA receberá o valor 77