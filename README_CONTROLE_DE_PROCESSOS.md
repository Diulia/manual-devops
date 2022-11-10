<h3> Comandos de Controlo de Processos </h3>

<!--ts--> 
* kill: Mata um processo, como por exemplo kill -kill 100 ou kill -9 100 ou kill -9 %1
* bg: Coloca um processo suspenso em background
* fg: Ao contrário do comando bg, o fg traz de volta um processo ao foreground
* jobs: Permite-nos visualizar jobs em execução, quando corremos uma aplicação em background, poderemos ver esse job com este comando, e termina-lo com um comando kill -9 %1, se for o jobnúmero 1, por exemplo

* top: Lista os processos que mais cpu usam, útil para verificar que processos estão a provocar um uso excessivo de memória, e quanta percentagem decpu cada um usa em dado momento

* ^y: Suspende o processo no próximo pedido de input
* ^z: Suspende o processo actual
<!--te--> 
