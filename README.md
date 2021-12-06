# exercicio-javascript

## Lista de Exercícios
1. Descrever um Algorítimo para resolver o problema da travessia de modo "seguro":

Umo homem precisa atravessar um rio com um barco que possui capacidade apenas para carregar ele mesmo e mais um de seus três pertences, que são: um lobo, uma cabra e um maço de alfafa. Em cada viagem só poderá ir o homem e apenas um de seus pertences. A seguinte regra deverá ser respeitada: o lobo não pode ficar sozinho com a cabra e nem a cabra sozinha com o maço de alfafa. Escreva um algorítmo para fazer a travissa dos pertences que estão em uma margem do rio para a outra.

Resposta:

Informações:
  * um barco com dois lugares
  * um homem
  * um lobo
  * um bode
  * um maço de alfafa
E que se ficarem sozinhos (sem a presença do homem):
  * lobo devora bode
  * bode devora alfafa

  - Levar o bode para a outra margem do rio
  - Voltar sem carga nenhuma para a margem oposta
  - Levar o lobo para a outra margem do rio
  - Voltar com o bode para a margem oposta
  - Deixar o bode na margem oposta
  - Atravessar com o maço de alfafa
  - Voltar sem carga
  - Levar o bode para a outra margem

2. JS: Exibir média de 3 números com entradas pelo formulário HTML
Enviar link(s) do git ou fiddle