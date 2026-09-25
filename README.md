# [090] Programación de Computadoras 1

Contenido, ejemplos y recursos del curso **Programación de Computadoras 1** (090), organizado por ciclo académico.

## 📁 Estructura

El repositorio está organizado por ciclo. Cada ciclo contiene una carpeta `Contenido/` con el material del curso según la estructura definida por el profesor/catedrático (semanas, proyectos, diseño curricular, opiniones del catedrático, etc.).

```
Ciclo-<Año>-<Semestre>/
└── Contenido/
    ├── Semana_1/
    ├── Semana_2/
    ├── ...
    ├── Proyecto 1/
    ├── Proyecto 2/
    ├── Diseño_Curricular/
    ├── Opinion_Catedratico/
    └── README.md
```

Ciclos disponibles actualmente:

- `Ciclo-2024-Primer-Semestre`
- `Ciclo-2024-Segundo-Semestre`
- `Ciclo-2025-Primer-Semestre`
- `Ciclo-2025-Segundo-Semestre`
- `Ciclo-2026-Primer-Semestre`
- `Ciclo-2026-Segundo-Semestre`

## 📥 Clonar

Puedes clonar el repositorio completo o descargar únicamente el ciclo que necesites.

### Clonar todo el repositorio

```bash
git clone https://github.com/CococysLabs/90-Programacion-de-Computadoras-1_Ejemplos.git
```

### Descargar solo un ciclo específico

Si no necesitas todo el historial de ciclos, puedes usar sparse-checkout para traer solo la carpeta que te interesa:

```bash
git clone --filter=blob:none --sparse https://github.com/CococysLabs/90-Programacion-de-Computadoras-1_Ejemplos.git nombre-carpeta
cd nombre-carpeta
git sparse-checkout set Ciclo-2025-Primer-Semestre
```

Donde:

- `nombre-carpeta` es el nombre que tendrá la carpeta descargada en tu computadora.
- `Ciclo-2025-Primer-Semestre` es el ciclo específico que deseas descargar (usa el nombre exacto de la carpeta).

## 🤝 Contribuir

Si deseas contribuir con material para este curso:

1. Haz fork del repositorio
2. Crea una rama: `git checkout -b feature/agregar-contenido`
3. Agrega tu contenido en el ciclo correspondiente (o crea uno nuevo siguiendo la estructura existente)
4. Commit: `git commit -m "feat: agregar [descripción]"`
5. Push y crea un Pull Request

## 📧 Contacto

- Email: cococys@ingenieria.usac.edu.gt
- Organización: [CococysLabs](https://github.com/CococysLabs)
