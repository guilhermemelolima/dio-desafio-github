# Configurado o Git <img src="../img/git.png" alt="image-git" width="4%" height="auto">

Para configurar o git usamos o seguinte comandos:

```bash
git config
```
- Permite visualizar e definir variáveis de configuração. As variáveis ficam armazenadas em três lugares:
  - --global Referente ao usuário logado na máquina;
  - --system Referente ao sistema como um todo e abrange a todos os usuários;
  - --local Configuração de um repositório específico.

<br>

```bash
git config --global user.name "nome"
git config --global user.email "emial@email.com"
```
- Permite definir o nome e email que apareceram nos registros.

<br>

```bash
git config init.defaultBranch
```
- Retorna o nome da breanch padrão.

<br>

```bash
git config --global init.defaultBranch main
```
- Configura a branch padrão para todos os repositórios como sendo 'main'.

<br>

```bash
git config --global --list
```
- Lista as configurações globais.

## 🔎 *Referências e Documentação*📗


- [Documentação Git](https://git-scm.com/doc)
- [Diagrama Markdow](https://support.typora.io/Draw-Diagrams-With-Markdown/)