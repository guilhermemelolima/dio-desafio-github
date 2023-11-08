# Salvando as alterações no repositório local

```bash
git add nome-arquivo
git add .
```
- O primeiro comando adiciona um arquivo a área de preparo enquanto o segundo adiciona todos os arquivos dentro do diretório para a área de trabalho;
- A área de preparo é um arquivo que exite dentro do diretório git, que contem os arquivos/diretórios que vão entrar no commit.

<br>

```bash
git commit -m "texto do commit"
```
- O comando commit registra as informações alteradas dos arquivos na branch, cada commit possui um código único chamado hash, um commit ainda pede uma mensagem breve que fala sobre as alterações;
- Este comando grava as alterações feitas, o momento que elas foram realizadas e o autor das alterações.

<br>

```bash
git commit --amend -m "nova mensagem"
git commit --amend  
```
- Esse comando permite modificar a mensagem de um commit, no primeiro caso a mensagem é alterada automaticamente quando executamos o comando;
- Caso não coloquemos uma mensagem o editor padrão configurado na instalação do git sera aberto para que seja feito as devidas alterações.
<br>

```bash
mkdir diretório-vazio
touch .gitkeep
``` 
- o arquivo ".gitkeep" é usado para preencher diretórios vazios, o git não consegue identificar diretórios vazios assim para que seja possível realizar o envio do diretório para o repositório remoto deve ser criado o arquivo ".gitkeep".

<br>

```bash
touch .gitignore
```
ou
```bash
echo diretório/ arquivo >> .gitignore
```
- O arquivo ".gitignore" lista os arquivos e diretórios que devem ser ignorados quando formos utilizar o comando "git add ." para realizar o envio das informações para o repositório remoto.

<br>

```bash
git .restore arquivo
```
- Com esse comando podemos restaurar um arquivo excluído ou modificado para a versão mais recente presente em um commit anterior.

<br>

```bash
git reset arquivo 
```
- Faz com que um arquivo retorne para uma versão presente em um commit anterior, ao executar este comando todas as alterações não confirmadas serão perdidas.

<br>


```bash
git restore --staged arquivo 
```
- Faz com que um arquivo que ainda não está na área de preparação tenha as alterações descartadas revertendo as alterações para a versão do último commit.

<br>

## 🔎 *Referências e Documentação*📗


- [Documentação Git](https://git-scm.com/doc)
- [Diagrama Markdow](https://support.typora.io/Draw-Diagrams-With-Markdown/)


<br>

### [Aula 3](resumo-aula3.md) 