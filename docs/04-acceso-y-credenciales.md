# Acceso y credenciales

## ⚠️ Importante sobre seguridad

El manual original incluía usuarios y contraseñas en texto. **Las credenciales reales NO se incluyen en este repositorio**, ya que GitHub es un sistema de control de versiones y cualquier dato subido (aunque se borre después) queda en el historial de commits de forma permanente.

### Recomendaciones

- Guardar las credenciales reales en un **gestor de contraseñas** (KeePass, Bitwarden, etc.) o en un fichero local **fuera del repositorio**.
- Si necesitas documentar credenciales en este repo, usa un fichero `credenciales.local.md` y añádelo al `.gitignore`.
- Nunca subir contraseñas, tokens ni claves de API a un repositorio, ni siquiera privado.

## Plantilla de referencia (rellenar localmente, NO subir)

```markdown
## Moodle local
- Usuario: ____________
- Contraseña: ____________

## Hosting Accounts (InfinityFree)
- Usuario: ____________
- Contraseña: ____________

## Área personal | Moodle (online)
- Usuario: ____________
- Contraseña: ____________
```

Guarda este bloque en un fichero `credenciales.local.md` en la raíz del proyecto. El `.gitignore` incluido en este repositorio ya excluye ese fichero para que nunca se suba por error.
