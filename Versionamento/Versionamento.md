## Versionamento

* Registro  de mudança de em arquivos,que possibilita recuperaçã ou acesso a versões anteriores;

* Desenvolvimento de códico em colaboração com outros integrantes;

> 1. Trabalho em equipe
> 
> 2. União de trabalho

## Git

E um sistema de versionamento de códico, que guarda os registro de versão como snapshots(fotos) do estado do projeto , alem de referencia/caminho para essa foto.

* Maioria das operações são feitas localmente 

* Faz a hash do códigos

### Instalação

```bash
git --version
```

> 1. **Github desktop** :limitados os comando em relação ao prompt
> 
> 2. **Vscode** 
>    
>    * GITLENS(extensão);

```bash
git config --global user.name "Nome de usuario"
git config --global user.email "usuario@email.com"
```

* Defini o nome do usuario e o e-mail

### Comandos

* ```bash
  git diff
  ```
  
  * O comando `git diff` é usado para comparar as alterações entre dois commits, branches ou outras referências no Git.

* ```bash
  git add <file>
  ```
  
  * O comando `git add` é usado para preparar alterações nos arquivos do seu repositório Git para serem registradas em um novo commit.

* ```bash
  git commit -m "mensagem"
  ```
  
  * é usado para criar um novo commit no repositório Git. Um commit é uma instantânea de um conjunto de alterações em seus arquivos, que é registrada no histórico do Git.
    
    * **Fazer de forma incremental**

* ```bash
  git log
  ```
  
  * É usado para exibir o histórico de commits de um repositório Git. Ele mostra uma lista de commits em ordem cronológica, com informações relevantes sobre cada commit, como o autor, a data, o hash do commit e a mensagem de commit associada.
