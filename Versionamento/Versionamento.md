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

&nbsp;

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

&nbsp;

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

* ```bash
  git restore
  ```
  
  * comando `git restore` é usado para desfazer alterações nos arquivos de um repositório Git. Ele pode ser utilizado para restaurar arquivos ao estado de um commit anterior ou para descartar alterações não adicionadas à área de preparação (staging area)

* ```bash
  git push <repositório-remoto> <branch-local>:<branch-remoto>
  ```
  
  * É usado para enviar as alterações locais do seu repositório Git para um repositório remoto. Especificamente, ele envia os commits e as referências (como branches) locais para o repositório remoto, mantendo-os sincronizados.

* ```bash
  git pull <repositório-remoto> <branch-remota>
  ```
  
  * O comando `git pull` é usado para atualizar seu repositório local com as alterações do repositório remoto. Em essência, ele combina duas operações Git: `git fetch` e `git merge`

* ```bash
  git branch <nome-da-nova-branch>
  ```
  
  * Uma branch é uma linha de desenvolvimento independente que pode conter um conjunto específico de alterações no projeto. O comando "git branch" permite aos desenvolvedores visualizarem todas as branches presentes em um repositório, bem como identificar a branch atual em que estão trabalhando.
  
  * ```bash
    git branch Nome
    ```

* `mermaid
graph LR;
  HEAD ---> p([master]);
  p    ---> a(commit 1)
  a    ---> b(commit 2);
  c([Nome]) ---> a;
```
  
  * ```bash
    git add ./file
    git commit -m "fazendo commit na branch MASTER"
    git push
    ```

* `mermaid
graph LR;
  HEAD         ---> p([master]);
  p            ---> b;;
  a(commit 1)  ---> b(commit 2);
  c([Nome])    ---> a;
```
