# ArduinoCodes
Arduino Codes

Visto de forma geral o que fora feito, fora usado um Arduino Uno R3, com sensor de distância ultrassônico ligados por quatros jumper na placa, quando o sensor capta algo no intervalo que fora programado para acionar algo passando, como se exemplo de um semáforo que está em vermelho, nesse dado momento é respondido o código com uma letra ao python (sendo ela a letra “c”), recebido essa letra o python roda um código que faz a câmera Ionic 3, tirar uma foto. Esta que atravez da bibliteca datatime, salva com o nome da data do dia que a foto fora tirada, esta que logo é levada e salvada na nuvem. 

Usualidade das bibliotecas:

hcsr04: esta biblioteca no Arduino fora usada para utilizar o sensor, através de que, qualquer objeto passar a menos de 2 metros ele irá responder com uma letra(c), e essa letra dar-se-á o comando para se tirar uma foto, com o nome do horário local e o dia.
Cv2: esta biblioteca é uma parte da biblioteca do OPENCV, que faz o processamento de imagem e auxilia no seu próprio uso. 
Data time: para definir o nome da imagem como o horário e o dia que fora feita. 
Serial: se utiliza esta biblioteca para se comunicar com a porta serial do Arduino. 
