# Fitxa tècnica: Configuració de Git i GitHub amb Visual Studio Code

## Objectiu

Aprendre a configurar Git, connectar-lo amb GitHub i gestionar versions d'un projecte mitjançant commits.

## Materials

- Ordinador amb Windows
- Visual Studio Code
- Git
- Compte de GitHub
- Connexió a Internet

## Procediment

1. Instal·lar Git a l'ordinador.
2. Crear un compte de GitHub.
3. Crear un repositori públic a GitHub.
4. Copiar l'URL HTTPS del repositori.
5. Clonar el repositori amb Visual Studio Code.
6. Modificar el fitxer README.md.
7. Desar els canvis.
8. Comprovar els fitxers modificats amb Git.
9. Crear un commit.
10. Enviar els canvis a GitHub amb Push.

### Comanda utilitzada

```bash
git status
```

Aquesta comanda mostra l'estat actual del repositori.

## Comprovacions

- [ ] Git instal·lat correctament
- [ ] Repositori clonat
- [ ] README modificat
- [ ] Commit realitzat
- [ ] Push enviat a GitHub

## Incidències i solucions

| Incidència | Solució |
|---|---|
| Error de configuració de Git | Executar `git config user.name` i `git config user.email` |
| Error d'autenticació amb GitHub | Tornar a iniciar sessió |
| No apareixen els canvis | Executar `git status` |

## Imatge

https://git-scm.com/images/logo@2x.png

## Recursos

- https://docs.github.com/
- https://git-scm.com/doc

## Flux de treball amb Git

El flux de treball habitual consisteix a modificar fitxers, revisar els canvis amb `git status` i `git diff`, afegir-los amb `git add`, crear un commit amb `git commit` i finalment sincronitzar-los amb GitHub utilitzant `git push`.
