# demo-alm-project

A simple starter project for Application Lifecycle Management (ALM) demonstrations.

## Project Structure

```
demo-alm-project/
├── src/                    # Source code
│   └── index.js            # Main placeholder file
├── tests/                  # Test suites
│   ├── unit/               # Unit tests
│   ├── integration/        # Integration tests
│   └── e2e/                # End-to-end tests
├── .github/
│   └── workflows/          # GitHub Actions workflows
│       └── test.yml        # CI workflow for running tests
└── README.md               # This file
```

## Getting Started

This project is a minimal starter template designed for ALM demonstrations.

## Running Tests

Tests are simulated via GitHub Actions. Check the Actions tab for workflow runs.


## 📂 Contenido del repositorio

| Archivo| Descripción |
|------------------|-------------|
| `RISK_REGISTER.md` | Registro de riesgos del proyecto (probabilidad, impacto, mitigación). |
| `INCIDENT_PLAYBOOK.md` | Guía de pasos a seguir en caso de incidentes. |
| `.github/ISSUE_TEMPLATE/bug_report.md` | Plantilla para reportar bugs. |
| `.github/ISSUE_TEMPLATE/incident_report.md` | Plantilla para reportar incidentes. |


## 1. Manejo de Riesgos

El archivo **`RISK_REGISTER.md`** incluye:
- Identificación de riesgos.
- Probabilidad.
- Impacto.
- Medidas de mitigación.
- Responsable.

**Ver archivo:** [RISK_REGISTER.md](./RISK_REGISTER.md)


## 2. Gestión de Issues

Las incidencias se documentan mediante:
- Plantillas para reportes.
- Severidad.
- Estado.
- Dueño de la investigación.
- Posible causa raíz.

**Plantilla:**  
- [Reporte de Bug](./.github/ISSUE_TEMPLATE/bug_report.md)  
- [Reporte de Issue](./.github/ISSUE_TEMPLATE/incident_report.md)


## 3. Playbook de Incidentes

Guía rápida para:
- Qué hacer cuando ocurre un incidente.
- Cuándo escalar.
- Cómo documentar un postmortem.

**Ver archivo:** [INCIDENT_PLAYBOOK.md](./INCIDENT_PLAYBOOK.md)