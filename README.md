# Examples

> Create and Switch to the New Branch
> 
> ```bash
>    git switch -c muratvuranok
> ```


> Make Changes and Commit
> 
> ```bash
>    git add .
>    git commit -am "Fixed Component"
> ```


> Push the New Branch to Remote Repository
> ```bash
> git push -u origin muratvuranok
> ```


## Rebase

> **Update the main branch**
> ```bash
>  git checkout main
> ```

> ```bash
>  git pull
> ```

> **Switch to Your Feature Branch**
> ```bash
>  git checkout muratvuranok
> ```

> **Start the Rebase**
> ```bash
> git rebase main 
> ```