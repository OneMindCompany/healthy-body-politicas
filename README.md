# healthy-body-politicas

Términos de uso y política de privacidad **públicos** del sistema **Healthy Body**, servidos con GitHub
Pages:

> - **https://onemindcompany.github.io/healthy-body-politicas/privacidad**
> - **https://onemindcompany.github.io/healthy-body-politicas/terminos**

Son las URLs que abren las apps desde Ajustes y desde la pantalla de la suscripción, y las que se declaran en las fichas de Google Play y de App Store.

## Ramas (estándar OneMind)

| Rama | Rol | Protegida |
|------|-----|-----------|
| `main` | Producción / versión publicada | ✅ |
| `qa` | Validación | ✅ |
| `develop` | Integración del trabajo en curso | ✅ |
| `feature/*` | Trabajo puntual, se integra a `develop` vía PR | ❌ |

Las tres ramas protegidas exigen pull request y bloquean borrado y `force-push`.
