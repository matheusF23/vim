# Shortcuts VIM

* Abrir arquivo:\
```
	$ vim nome_do_arquivo

	$ vim diretorio/outro_diretorio/nome_do_arquivo
```

* Modos:

O VIM tem alguns modos:

	- modo normal. Já abre nesse modo, ou se estiver em outro modo é só usar o ESC.
	- modo de inserção (i).
	- modo de visualização (v).
	- modo de comando.

* Movimentação dentro do texto (**modo normal**)\
	- **h**: esquerda
	- **j**: baixo
	- **k**: cima
	- **l**: Direita

	- Para ir ao final do arquivo: **G**
	- Para voltar ao topo: **gg**
	- Para mover ao final de uma palavra: **e**
	- Para mover até o começo da próxima palavra: **w**
	- Para mover ao próximo caractere especifico use: **f[caractere]**. Ex: **f(** para ir ao próximo (
	- Para mover ao começo de uma linha: **0**
	- Para mover ao final de uma linha: **$**
	- Para pular ao final de um parágrafo: **]**
	- Para pular para o fechamento de um parenteses/colchete/chaves: **%**

	Da para formar comandos com cotadores para agilizar ainda mais. Por exemplo, para pular 10 linhas no texto: **10j**

* Inserindo texto
	- entrar no modo de inserção: **i**
	- entrar no modo de inserção no começo da linha: **I**
	- entrar no modo de inserção na frente de onde o cursor se encontra: **a**
	- entrar no modo de inserção no final da linha: **A**
	- adicionar uma linha abaixode onde estiver o cursor e entrar no modo de inserção: **o**
	- adicionar uma linha acima e entrar no modo de inserção: **O**

* Apagar um texto (modo normal)
	- deletar o caractere onde o cursor estiver: **x**
	- deletar o caractere de trás do cursor: **X**
	- deletar a partir do cursor até o começo da próxima palavra: **dw**
	- deletar do cursor até o fim da linha: **d$**
	- deletar a linha inteira, incluindo o [ENTER] que houver no final: **dd**
	- deletar de onde o cursor estiver até o final da linha e entrar em modo de iserção a partir dali: **C**
	- deletar do cursor até o final palavra e entrar em modo de inserção: **ce**

	**obs:** ao deletar, o que for deletado ficará em cache podendo ser colado com p no modo normal.

* Copiar, colar, recortar
	- copiar: **y**. é preciso selecionar um texto; para isso, entre no modo de visualização (v) e use as teclas de movimentação.
	- colar: **p**
	- copiar uma linha inteira: **yy**
	- recortar: usar os comandos de deletar

* Desfazer/refazer alguma coisa
	- desfazer a ultima alteração: **u**
	- desfazer todas as alterações efetuadas em uma linha inteira: **U**
	- refazer a ultima coisa que foi desfeita: **ctrl+R**

* Localizar uma palavra dentro do texto
	- no modo normal use **/**, digite o texto e pressione **ENTER**
	- para pular para a próxima ocorrência: **n**
	- para voltar para a ocorrência anterior: **N**

* Salvar o sair de um arquivo (modo de comando)
	- sair: **:q**. Alterações precisam estar salvas.
	- sair sem salvar, descartar alterações: **:q!**
	- salvar: **:w**
	- salvar e sair: **:wq**
	- salvar arquivo com outro nome: **:w novo_nome**
	- no modo normal, pode-se usar **ZZ** para salvar e sair.

* Outros comandos
	- **:Vex** -> splitar a tela mostrando o diretório atual 
	- **:split** -> split horizontal
	- **:vsplit** -> split vertical
	- **ctrl w duas vezes** -> alternar entre as janelas splitadas. ou pode usar **ctrl w** e inidicar a direção que quer mudar.

