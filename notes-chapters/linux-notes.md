# LPIC-1 - Bóson treinamentos
## Notes

###Comando APT-GET 
   * apt-get --purge  / Remover um pacote dá raiz.
   * apt-get remove   / Remover o pacote, mais não a raiz.
   * apt-get upgrade  / Atualizar todos os pacotes instalado, usando a opção -U consegue ver quais os pacotes será atualizado.
   * apt-get install  / Instalar qualquer pacote.

###Comando APT-CACHE
   * apt-cache search palavra-chave / Pesquisa de pacotes por palavra chave.
   * apt-cache search palavra-chave  | less / Filtra a informações.
   * apt-cache pkgnames / Pesquisa todos os nome dos pacotes existente.
   * apt-cache show pacote / Mostrar informações do pacote. 
   * apt-cache rdepends / Mostrar quais dependencia o pacote exige pra ser instalado.

###Comando Aptitude 
	> Todas funcionabilidade praticamente que tem o apt-get.
   * aptitude install / Instalar pacotes.
   * aptitude search palavra-chave / Pesquisar por nome de pacote.
   * apttitude purge / Remover até a raiz.
   * apttitude remove / Remover, mais não até a raiz.