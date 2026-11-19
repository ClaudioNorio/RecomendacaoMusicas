# RecomendacaoMusicas
Descrição
O modelo de dados é simples, pois temos poucos nós. Os nós são: musica, cantor, compositor, álbum, pessoa e gênero. Os relacionamentos são: compõe, interpreta, curte, compra, segue, pertence, ouve, pode ser, faz_parte  

Como se trata de recomendações de músicas, temos que procurar perfis de pessoas similares. Para isso, precisamos considerar alguns critérios para procurarmos os perfis similares. No caso de gênero musical, procurar as pessoas que gostam dos mesmos gêneros (neste caso, 1 gênero já é suficiente).  No caso de cantores, pessoas que curtem cantores em comum (acima de 2 cantores). No caso de album, pessoas que compram o mesmo album. Posto os critérios precisamos procurar os perfis similares considerando todos numa pesquisa conjunta. 
Se encontramos, obtemos as músicas que uma pessoa ouve e as recomendamos para outra pessoa dentro de cada perfil identificado. As músicas que as 2 pessoas ouvem em comum devem ser retiradas da lista de recomendações.

Tenho amostras dos arquivos de carga (cantor.csv e musicas.csv). O modelo de dados (RecomendaMusica.svg) e as instruções cypher para criar nós e relacionamentos. A última instrução traz o comando cypher para fazer as recomendaçõe de músicas.
