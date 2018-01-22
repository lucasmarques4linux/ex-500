## Atividades para prática de conhecimento sobre include e require.

### INCLUDE

1. Crie três arquivos: **pessoa.php**, **cargo.php** e **empresa.php**;
2. Dentro do arquivo **cargo.php**, crie uma variável chamada **cargo** e atribua um valor à ela;
3. Dentro do arquivo **pessoa.php**, inclua o arquivo anterior e crie duas variáveis chamadas **nome** e **idade**;
4. Dentro do arquivo **empresa.php**, inclua o arquivo anterior e cria uma variável chamada **empresa**;
5. Cria um arquivo chamado **view.php** e inclua o arquivo anterior.
6. Ainda no arquivo **view.php**, exiba a mensagem:
> Olá, meu nome é *{nome}*, tenho *{idade}*, atualmente trabalho como *{cargo}* na empresa *{empresa}*;

### REQUIRE_ONCE

1. Crie uma pasta e coloque os arquivos deste exemplo dentro dela;
2. Crie cinco arquivos: **rodape.php**, **topo.php**, **contato.php**, **pagina_inicial.php** e **sobre.php**;
3. Dentro do arquivo **topo.php**, crie uma estrutura *HTML* com links para as páginas **pagina_inicial.php**, **sobre.php** e **contato.php**;
4. Dentro do arquivo **rodape.php**, termine a estrutura e coloque um paragrafo com a mensagem *rodape*;
5. Dentro dos arquivos **pagina_inicial.php**,**sobre.php** e **contato.php**, faça o requerimento do arquivo de **topo.php**, escreva uma mensagem diferente em cada arquivo e depois faça o requerimento do arquivo de **rodape.php**;
6. Ao final deste exemplo você deverá ter uma estrutura de navegação entre as três páginas **pagina_inicial**, **sobre** e **contato**, onde o **topo** e o **rodape** estarão aparecendo em todas;