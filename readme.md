# Viajes en el pasado con git y github

si quieres volver atras:

```
git log --oneline
```

copias el punto donde quieres volver, ejemplo 123abc

```
git reset --hard 123abc
```

y para que se actualice en github

```
git push origin HEAD --force
```

PAra Revertir merges

```
git revert -m 1 <SHA-code>
git push origin <branch>
```
