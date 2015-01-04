# LPIC-1 - Bóson treinamentos
## Notes

 
###Comandos Básicos 
| Comandos       | Funcionalidade                                                                         | Manual            |
| -------------- | :----------------------------------------------------------------------------------:   | --------------:   |
| **ls**         | *Listagem de conteúdo.*                                                                | **[man comando]** |
| **chgrp**      | *Mudança propriedades de grupos*                                                       | **[man comando]** |
| **chmod**      | *Mudança permissões de diretórios e arquivos*                                          | **[man comando]** |
| **rm**         | *Apagar arquivos*                                                                      | **[man comando]** |
| **rmdir**      | *Apagar diretórios*                                                                    | **[man comando]** |
| **mv**         | Mover diretórios e renomear arquivos ou pastas*                                        | **[man comando]** |
| **cp**         | *Copiar arquivos e diretórios*                                                         | **[man comando]** |
| **cat**        | *Vizualizar o que está escrito dentro do arquivo e cocatenar vários arquivo pra um só* | **[man comando]** |
| **split**      | *Dividir arquivos*                                                                     | **[man comando]** |
| **touch**      | *Criação de arquivo e modificar tempo,data, hora de um arquivo ou diretorio*           | **[man comando]** |
| **clear**      | *Limpar a tela do bash*                                                                | **[man comando]** |


###Comando APT-GET 
   > * apt-get --purge  / Remover um pacote dá raiz.
   > * apt-get remove   / Remover o pacote, mais não a raiz.
   > * apt-get upgrade  / Atualizar todos os pacotes instalado, usando a opção -U consegue ver quais os pacotes será atualizado.
   > * apt-get install  / Instalar qualquer pacote.

###Comando APT-CACHE
   > * apt-cache search palavra-chave / Pesquisa de pacotes por palavra chave.
   > * apt-cache search palavra-chave  | less / Filtra a informações.
   > * apt-cache pkgnames / Pesquisa todos os nome dos pacotes existente.
   > * apt-cache show pacote / Mostrar informações do pacote. 
   > * apt-cache rdepends / Mostrar quais dependencia o pacote exige pra ser instalado.

###Comando Aptitude 
	> Todas funcionabilidade praticamente que tem o apt-get.
   > * aptitude install / Instalar pacotes.
   > * aptitude search palavra-chave / Pesquisar por nome de pacote.
   > * apttitude purge / Remover até a raiz.
   > * apttitude remove / Remover, mais não até a raiz.
