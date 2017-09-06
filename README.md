# Criptografia Simétrica DES

## Bibliografia

## Receita de instalação

```sh
# Primeiro instale o texlive-full
sudo apt-get install texlive-full

# Depois instale os pacotes para o abntex
apt-get install texlive-publishers texlive-lang-portuguese texlive-latex-extra texlive-fonts-recommended

# Baixe o abntex ou acesse http://dl.bintray.com/laurocesar/generic/abntex2.tds-1.9.6.tar.gz no navegador
wget http://dl.bintray.com/laurocesar/generic/abntex2.tds-1.9.6.tar.gz

# Descompacte o abntex dentro de alguma pasta, ou use o comando
tar xfvz abntex2.tds-1.9.6.tar.gz

# Entre na pasta descompactada e instale usando
sudo make install
```

## Receita para compilar

```sh
# Instale o pdflatex
sudo apt-get install pdflatex

# Entre na pasta src e rode
pdflatex criptografia-simetrica-des.pdf

```