Backup antes de mejoras del blog
================================

Se generó un respaldo antes de realizar cambios mayores en el blog.

- Rama remota creada: backup-before-blog-20260528
- Tag anotado creado: backup-before-blog-20260528
- Git bundle: C:\Users\sandra\AppData\Local\Temp\backup-before-blog-20260528.bundle
- ZIP del worktree: C:\Users\sandra\AppData\Local\Temp\worktree-backup-20260528.zip

Cómo volver a la copia de respaldo (pasos rápidos):

1. `git fetch origin --tags`
2. `git checkout -b restore-backup backup-before-blog-20260528`
3. Si necesitás forzar master al estado del backup (coordinar antes):
   - `git checkout master`
   - `git reset --hard backup-before-blog-20260528`
   - `git push --force-with-lease origin master`

No uses `git push --force` en ramas compartidas sin coordinación.
