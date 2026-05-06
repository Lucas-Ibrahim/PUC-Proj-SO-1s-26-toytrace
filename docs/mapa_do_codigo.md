Onde o programa começa: O programa comeca no arquivo main.c que chama cli e trace_runtime.

Onde o processo alvo é criado: O processo alvo é criado no arquivo trace_runtime.c.

Onde o runtime chama o callback: O runtime chama o callback dentro da funcao trace_program() em "observer(&ev, userdata);".

Quais arquivos o grupo deve modificar: Os arquivos que precisamos modificar são trace_runtime.c, formatter.c, pairer.c

Qual TODO aparece primeiro ao executar o scaffold: "erro: TODO Semana 2: implementar launch_tracee()".

Qual é a principal dúvida técnica do grupo neste momento: Dificuldade em ler e entender o código em si.


Mapa mental do código:

![alt text](<Pasted Graphic 1.jpg>)