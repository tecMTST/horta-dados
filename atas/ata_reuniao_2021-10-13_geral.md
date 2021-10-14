# Reunião de dados da horta (13/10/2021) - 20:00

## Presentes

* Renato
* Cesar Coelho
* Henrique Xavier
* Kauê
* Robson
* Daniel
* Willian

## Discussões

* Deixar o hardware pronto para receber os sensores futuros (e.g. meteorológicos).
* Ter um único sensor de fluxo para economizar, regar um canteiro por vez.
* Lógica de rega fica no módulo.
* Robson falou da infra da nuvem, as demais pessoas não tem tanto conhecimento no assunto. Robson falou que levantou os serviços na Oracle, mas ainda não comparou com AWS e GCP.
* Processamento automático de dados seria feito em servidor/serviço à parte.

## Produtos plantados

* Beringela
* Chuchu
* Alface
* Almeirão
* Cebola
* Batata doce
* Coentro
	
## Descrição do hardware

### SISTEMA MODULO:

#### SENSORES (LÊ):
* umidade do solo -> 0.0 a 100.0 %UR
* umidade do ar -> 0.0 a 100.0 %UR
* temperatura do ar -> 0.0 a 50.0 ºC;
* luminosidade -> 0 a 40.000 Lux;
* fluxo de água -> 1 a 30 L/min;

#### CONTROLE (LÊ):
* Nível da bateria -> 0 a 100 %;
* Bateria carregando -> 0 a 1;

#### ATUADORES (ESCREVE):
* válvula solenoide de água -> 0 a 1;

### GATEWAY:

#### CONTROLE (LÊ):
* Nível da bateria -> 0 a 100 %;
* Bateria carregando -> 0 a 1;
* Data -> DDMMAA;
* Hora -> HHMMSS;

### WEB:
* input manual PH solo -> 0 a 14;

