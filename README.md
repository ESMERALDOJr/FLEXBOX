# FLEXBOX
## Display-flex:
Conhecendo e aplicando a propriedade de inicialização do flex container. Podemos transformar a tag em elemento do tipo flex container, e assim automaticamente todos
os seus filhos diretos desta tag, tornam-se em flex items.

## Flex-direction: 
Entendendo o comportamento padrão de orientação horizontal de um flex container e aprendendo a modificar a orientação horizontal. 
O Flex-direction é a propriedade que estabelece o eixo principal do container, definindo assim a dereção que os flex items são colocados no flex container.<br>
* row(padrão): à direção do texto, esquerda para direita.
* row-reverse: sentido oposto à direção do texto.
* column: ordenação de cima para baixo, em coluna única.
* column-reverse: ordenação inversa, de baixo para cima.

## Flex-wrap: 
É a propriedade que define se os itens devem ou não quabrar a linha. Por padrão eles não quebram linhas, isso faz com que os *flex items* sejam compactados além do limite do conteúdo.
* nowrap: é o padrão, não permite a quebra de linha.
* wrap: permite a quebra de linhas assim que um dos flex items não puder mais ser compactado, porém na direção contrária da linha, acima.

## Flex-flow:
É um atalho para  as propriedades **flex-direction** e **flex-wrap.** Porém seu uso não é tão comum, visto que, quando mudamos o flex-direction para column, mantemos o padrão do flex-wrap que é nowrap.

## Justify Content:
Essa propriedade vai se encarregar de alinhar os itens dentro do container de acordo com a direção pretendida e tratar da distribuição de espaçamento entre eles.<br>
***OBS:*** caso seus itens estajam oculpando 100% de todo o container, ele não se aplica.
### As variações:
* **flex-start:** início do container.
* **flex-end:** final do container.
* **center:** ao centro do container.
* **space-between:** cria um espaçamento igual entre os elementos.
* **space-around:** os espaçamentos do meio são duas vezes maiores que o inicial e final.

## Align-items:
Trata do alinhamento dos flex items de acordo com o eixo do container.<br> O alinhamento é diferente para quando os itens estão em colunas ou linhas.<br> permite o alinhamento central no eixo vertical.
### Tipos de alinhamento:
* **center:** alinhamento dos itens ao centro
* **stretch:** padrão, e os flex items crescem igualmente
* **flex-start:** alinhamento dos itens no início
* **flex-end:** alinhamento dos itens no final
* **baseline:** alinhamento de acordo com a linha base da tipografia dos itens

## Align-content:
Precisamos que:
* O container utilize quebra de linhas
* A altura do container seja maior que a soma das linhas dos itens
### Tipos de alinhamento
* **center:** alinhamento dos itens ao centro
* **stretch:** é o padrão e os flex items crescem igualmente
* **flex-start:** alinhamento dos itens no início
* **flex-end:** alinhamento dos itens no final
* **space-between:** cria um espaçamento igual entre os elementos
* **space-around:** os espaçamentos do meio são duas vezes maiores que o inicial e final








