# Como instalar e configurar para usar LATEX em seu computador

## Em Linux

---

### Baixando o Programa Tex Live

* Baixe o programa `texlive` em seu computador.
  * `sudo apt-get install texlive`
* Coloque o PATH direto

* Temos então que baixar os pacotes necessário para usar
* Para baixar: `sudo apt-get install nomePacote`
* Abaixo alguns pacotes que se pode baixar

Nome do Pacote|Para que serve|Comando
|---|---|---|
Tipos extras para LATEX|Pacotes necessários de Latex|`texlive-latex-extra`
Para escrever em Portugues|Pacote com a linguagem Portuguesa|`texlive-lang-portuguese`
Pacotes Básicos de LATEX|Pacote genérico de Latex|`texlive-generic-extra`

### Compilando um arquivo tex

* Quando baixamos o Tex Live ele traz o programa **pdflatex**
* Para iniciar o programa, abra um terminal: `CTRL + ALT + T`
* Coloque o seguinte comando:
  * `pdflatex nomeArquivo.tex`
* Ele vai iniciar o programa e transformar o arquivo em pdf,criando um arquivo **.aux** e um arquivo **.log**
* Se aparecer uma mensagem dizendo que não reconheceu o arquivo **.aux** no terminal e aparecer um **?** simplesmente coloque um **r** para tentar novamente

<img src="images/pdflatex.gif">

---
