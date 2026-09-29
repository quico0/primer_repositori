# Fitxa tècnica: Creació d'un repositori GitHub i ús de Visual Studio Code

## Objectiu

Crear un compte de GitHub, generar un repositori públic, clonar-lo amb Visual Studio Code i sincronitzar els canvis utilitzant Git.

## Materials

- Ordinador amb connexió a Internet
- Compte de GitHub
- Visual Studio Code
- Git

## Procediment

1. Accedir a GitHub i crear un compte.
2. Verificar les adreces de correu electrònic.
3. Crear un repositori públic anomenat primer_repositori.
4. Crear el fitxer README.md.
5. Copiar l'URL del repositori.
6. Clonar el repositori amb Visual Studio Code.
7. Editar el fitxer README.md.
8. Guardar els canvis.
9. Executar la comanda git add.
10. Crear un commit.
11. Sincronitzar els canvis amb GitHub.

## Comprovacions

- [ ] El compte de GitHub està creat correctament.
- [ ] El repositori és visible a GitHub.
- [ ] El fitxer README.md s'ha actualitzat.
- [ ] Els canvis apareixen al repositori remot.

## Incidències i solucions

| Incidència | Solució |
|---|---|
| Error d'autenticació | Tornar a iniciar sessió a GitHub |
| No apareixen els canvis | Executar git push origin main |
| Error en clonar el repositori | Verificar l'URL del repositori |

## Imatge

![Captura repostiori](./media/captura-repositori.png)

## Bloc de codi

```bash
git status
git add .
git commit -m "Afegeix presentació inicial"
git push origin main
```

## Recursos

- [01-iniciació git GitHub i Visual Studio Code](https://github.com/SMX-ProjecteIntermodular/Projecte2/blob/main/guies/01-iniciacio-git-github-vscode.md)

## Flux de treball amb Git

1. Modificar fitxers.
2. Revisar els canvis amb git status.
3. Comprovar les diferències amb git diff.
4. Afegir els canvis amb git add.
5. Crear un commit amb git commit.
6. Sincronitzar amb git push.