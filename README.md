# Converter-Celsius-para-Fahrenheit.
Este código é um simples conversor de temperatura de Celsius para Fahrenheit. Ele solicita ao usuário a entrada da temperatura em graus Celsius, realiza o cálculo da conversão para Fahrenheit e, em seguida, imprime o resultado na tela.

Vamos analisar linha a linha:

temperatura = float(input('Informe a temperatura em ºC: '))

Nesta linha, a função input() é usada para solicitar ao usuário a entrada de um valor. O texto 'Informe a temperatura em ºC: ' é exibido na tela para instruir o usuário a inserir o valor de temperatura em graus Celsius. A função float() é usada para converter o valor de entrada em um número decimal (flutuante) e, em seguida, atribuir o valor a variável temperatura.

resultado = (temperatura * 9/5) + 32

Nesta linha, a variável resultado é atribuída o resultado do cálculo da conversão da temperatura de Celsius para Fahrenheit. A fórmula matemática para a conversão é: (temperatura em Celsius × 9/5) + 32. O resultado é armazenado na variável resultado.

print('A temperatura de {:.1f}ºC corresponde a {:.1f}ºF!'.format(temperatura, resultado))

Nesta linha, a função print() é usada para exibir a mensagem "A temperatura de XX.XºC corresponde a YY.YºF!", onde XX.X é o valor de temperatura em graus Celsius inserido pelo usuário e YY.Y é o valor convertido em graus Fahrenheit. O método format() é usado para inserir os valores das variáveis temperatura e resultado na mensagem a ser exibida. O formato :.1f é usado para mostrar apenas uma casa decimal após o ponto.
