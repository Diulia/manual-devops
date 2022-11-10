<h3>Comandos de Gestão de Arquivos e Directorias</h3>

<!--ts-->
* cd: Mudar de diretório atual, como por exemplo cd diretório, cd .., cd /
* chmod: Mudar a proteção de um arquivo ou diretório, como por exemplo chmod 777, parecido com o attrib do MS-DOS
* chown: Mudar o dono ou grupo de um arquivo ou diretório, vem de change owner
* chgrp: Mudar o grupo de um arquivo ou diretório
* cmp: Compara dois arquivos
* comm: Seleciona ou rejeita linhas comuns a dois arquivos selecionados
* cp: Copia arquivos, como o copy do MS-DOS
* crypt: Encripta ou Descripta arquivos (apenas CCWF)
* diff: Compara o conteúdo de dois arquivos ASCII
* file: Determina o tipo de arquivo
* grep: Procura um arquivo por um padrão, sendo um filtro muito útil e usado, por exemplo um cat a.txt | grep ola irá mostrar-nos apenas as linhas do arquivo a.txt que contenham a palavra “ola”

* gzip: Comprime ou expande arquivo
* ln: Cria um link a um arquivo
* ls: Lista o conteúdo de uma diretório, semelhante ao comando dir no MS-DOS
* lsof: Lista os arquivos abertos, vem de list open files
* mkdir: Cria uma diretório, vem de make directory”
* mv: Move ou renomeia arquivos ou diretórios
* pwd: Mostra-nos o caminho por inteiro da diretório em que nos encontramos em dado momento, ou seja um pathname
* quota: Mostra-nos o uso do disco e os limites
* rm: Apaga arquivos, vem de remove, e é semelhante ao comando del no MS-DOS, é preciso ter cuidado com o comando rm * pois apaga tudo sem confirmação por defeito

* rmdir: Apaga diretório, vem de remove directory
* stat: Mostra o estado de um arquivo, útil para saber por exemplo a hora e data do último acesso ao mesmo
* sync: Faz um flush aos buffers do sistema de arquivos, sincroniza os dados no disco com a memória, ou seja escreve todos os dados presentes nos buffers da memória para o disco

* sort: Ordena, une ou compara texto, podendo ser usado para extrair informações dos arquivos de texto ou mesmo para ordenar dados de outros comandos como por exemplo listar arquivos ordenados pelo nome

* tar: Cria ou extrai arquivos, muito usado como programa de backup ou compressão de arquivos
* tee: Copia o input para um standard output e outros arquivos
* tr: Traduz caracteres
* umask: Muda as proteções de arquivos
* uncompress: Restaura um arquivo comprimido
* uniq: Reporta ou apaga linhas repetidas num arquivo
* wc: Conta linhas, palavras e mesmo caracteres num arquivo
<!--te-->