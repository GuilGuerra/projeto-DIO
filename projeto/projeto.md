# Desafio Git e Github DIO :mortar_board:

### *Desafio repositório no GitHub*

Para esse desafio achei interessante colocar uma lista com as 5 linguagens de programação mais usada no mundo e no Brasil, de acordo com o GitHub.

O Octoverse Report, como o levantamento é chamado, revela que estas foram *as cinco linguagens de programação* que *mais* avançaram no mundo em 2021:

1. JavaScript
2. Python
3. Java
4. TypeScript
5. C#

Já a lista referente ao mercado brasileiro de desenvolvimento de software é esta (ela só foi divulgada para a imprensa):

1. JavaScript
2. Sass CSS
3. Blade
4. HCL
5. Elixir

##### *Fonte: https://tecnoblog.net/noticias/2022/01/24/as-5-linguagens-de-programacao-mais-usadas-no-brasil-segundo-o-github/*

# Formatações do Markdown :bulb:

https://markdown.net.br/sintaxe-basica/#:~:text=A%20formata%C3%A7%C3%A3o%20mais%20simples%20do,processador%20Markdown%20interpretar%C3%A1%20como%20par%C3%A1grafos.



# Comandos Básicos para o Git :computer_mouse:



### **Git add**

Este comando adiciona os arquivos solicitados ao ambiente de stage, é uma forma de dizer para o git que você deseja que as modificações daquele arquivo sejam gravadas na próxima remessa. Um exemplo de utilização é: git add . onde o ponto representa todos os arquivos na pasta.

### **Git commit**

Agora fazemos a gravação em si das modificações, desta forma criamos um snapshot do estado atual do nosso projeto. Uma forma muito usada é o git commit -m “descrição das atualizações do projeto” onde o -m é uma flag que aponta para a mensagem de descrição.

### **Git push**

Por fim precisamos subir essas modificações no nosso repositório remoto, para isso basta utilizar o comando git push e, se já estiver tudo devidamente configurado, os arquivos serão salvos no repositório remoto correspondente ao seu repositório local!

### **Git status**

Este comando permite ver quais arquivos estão sendo “rastreados” pelo git e quais modificações já foram enviadas para o stage. É bem útil para quando se tem dúvidas sobre o que está sendo enviado

### **Git branch**

É usado para verificar todas as branches presentes no repositório. Ao utilizar a flag -r no final do comando é possível ver todas as branches presentes no repositório remoto e se você quiser criar uma nova branch basta utilizar este comando: git branch <branch_name>.

### **Git checkout**

É o comando utilizado para trocar de branch passando o nome da branch destino no final do comando. Caso a flag -b seja colocada após o “checkout” é possível criar a branch em questão e já trocar para esta imediatamente.

E aí, o que achou desta dose de git? Vale lembrar que esta é uma ferramenta muito versátil e tem muito mais funcionalidades do que poderíamos cobrir aqui, portanto não deixe de buscar mais informações para se especializar neste que é o sistema de versionamento mais utilizado do mundo!

##### 									*Fonte: https://www.digitalhouse.com/br/blog/principais-comandos-git*