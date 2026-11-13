# Planner para Codex

Conector para usar [Planner](https://planner.tigo.plus) desde Codex (terminal o escritorio): proyectos, actividades, sprints, módulos y comentarios, con tu propia cuenta y tus permisos.

No necesitas copiar ningún token. La primera vez, Codex abre Planner en el navegador; si ya tienes la sesión abierta, solo pulsas **Permitir**.

## Instalar

```sh
codex plugin marketplace add tecnologia01/planner-codex-plugin
codex plugin add planner@planner
```

En Codex de escritorio también puedes instalarlo desde la lista de plugins una vez añadido el marketplace.

Si el navegador no se abre solo o la conexión caduca (cada 90 días):

```sh
codex mcp login planner
```

## Sin plugin

```sh
codex mcp add planner --url https://planner.tigo.plus/mcp
codex mcp login planner
```

## Desconectar

Revoca el token "Codex" desde tu perfil en Planner, o ejecuta `codex mcp logout planner`.

## Requisitos

Acceso a `planner.tigo.plus` desde tu equipo y una cuenta activa en Planner.
