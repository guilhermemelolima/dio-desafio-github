![Banner Git e Github](img/banner-git-github.png)

# DIO | Resumos Git e GitHub

Repositório com resumos provenientes do curso de versionamento de código com Git e Github

[***Cerificado***](https://www.dio.me/certificate/5B414621/share)

## *Comandos basicos do bash*

- #### TAB -  auto completa o nome de um arquivo ou diretório

### Criar diretório
```bash
mkdir diretório

mkdir -p diretório-1/diretório-2
```
* O primeiro comando possibilita criar um diretório, o segundo comando permite que seja criado o diretório-1 e dentro tenha o subdiretório diretório-2.

### Navegar pelos diretórios
```bash
cd nome-diretório

cd ..
cd ../nome-diretório

cd ~/
cd ~/nome-do diretório

cd /
```
* Este comando possibilita navegar por diretórios entrando neles como no primeiro caso ou voltando para o anterior usando os dois pontos. O '~' é uma espécie de abreviação para a home do usuário, e colocando apenas o '/' somos direcionados para a raiz do sistema.

### Listar conteudos
```bash
ls diretório

ls -l diretório

ls -lah diretório
```
* Lista os conteúdos dentro do diretório, no primeiro caso temos o retorno mais básico sendo apenas uma sequência dos nomes;
* No segundo caso os arquivos e diretórios nos são apresentados na forma de lista com algumas informações importantes como permissões do arquivo/diretório, proprietário, grupo, tamanho, data de modificação e nome do arquivo;
* O terceiro caso é semelhante ao anterior, mas temos duas diferenças, o 'a' mostra arquivos ocultos contidos no diretório, e o 'h' mostra o tamanho dos arquivos de forma legível para humanos.

### Criar arquivo
```bash
touch arquivo
```
- Possibilita criar um arquivo vazio.

```bash
echo "texto" > arquivo

echo "texto" >> arquivo
```
- Os dois comandos funcionam de maneira parecida, ambos criam um arquivo, mas o primeiro sobre escreve todo o conteúdo do arquivo com o texto passado já o segundo adiciona na última linha o texto passado.

### Excluir arquivos e diretórios
```bash
rm -f arquivo
rm -rf diretório
```
- Os dois comandos podem ser usado para remover arquivos ou diretórios, mas para que funcione é preciso utilizar a opção certa no caso "-f" para arquivos e "-rf" para diretórios

### Mostrar conteudo dentro de um arquivo
```bash
cat arquivo

cat -n arquivo
```
- O primeiro comando exibe o conteúdo de um arquivo, no segundo mostra o conteúdo mais o número de linhas do arquivo.

### Editor de código 
```bash
nano arquivo
```
* Este comando faz com que o arquivo seja executado dentro de um editor de código simples, mas útil para pequenas edições.

## 💻 *Resumo das aulas*
| Aulas | Resumos |
| :------ | :------:|
| Versionamento | [Resumo](resumos/resumo-aula1.md) |
| Configurando o Git | [Resumo](resumos/resumo-aula2.md) |
| Criando e Cloando Repositórios | [Resumo](resumos/resumo-aula3.md) |
| Gravando alterações no Repositório Local | [Resumo](resumos/resumo-aula4.md) |


## 🔎 *Referências e Documentação*📗

- [Digital Inovation One](https://https://www.dio.me/)
- [Documentação Git](https://git-scm.com/doc)
- [Docuemntação GitHub](https://dosc.github.com/)
- [Comando bash | GNU/Linux](https://guialinux.uniriotec.br/)
- [Diagrama Markdow](https://support.typora.io/Draw-Diagrams-With-Markdown/)

## Links Úteins
- [Sintaxe Markdown](https://markdownguide.org/basic-syntax/)
