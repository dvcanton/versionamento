## Versionamento semântico
(exemplo NPM)

    MAJOR.MINOR.PATCH

-   `MAJOR`: mudaças incompativeis com APIs anteriores
-   `MINOR`: novas funcionalidades, porém mantem compatibilidade com versões anteriores
-   `PATCH`: bug fixes (backward-compatible!)

## Releases baseado no tempo

#### Vantagens: 
Feedback constante entre desenvolvedores e usuarios.

#### Escalas de tempo: 
 - todo merge 
 - uma vez por semana
 - uma vez ao mês
 
Exceção: security fixes


## Git
Tim Pope (desenvolveu diversos plugins para o Vim) dá exemplo de um commit:

```
Capitalized, short (50 chars or less) summary

More detailed explanatory text, if necessary.  Wrap it to about 72
characters or so.  In some contexts, the first line is treated as the
subject of an email and the rest of the text as the body.  The blank
line separating the summary from the body is critical (unless you omit
the body entirely); tools like rebase can get confused if you run the
two together.

Write your commit message in the imperative: “Fix bug” and not “Fixed
bug” or “Fixes bug.”  This convention matches up with commit messages
generated by commands like git merge and git revert.

Further paragraphs come after blank lines.

- Bullet points are okay, too

- Typically a hyphen or asterisk is used for the bullet, followed by a
  single space, with blank lines in between, but conventions vary here

- Use a hanging indent
```


## Integrando versionamento com testes
- CircleCI
- Travis
- Jenkins
- AppVeyor
