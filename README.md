# Sistema de Gestión para Clases de Spinning
Repositorio correspondiente a la práctica de laboratorio 4. Contiene los modelos de análisis del **Sistema de Gestión de Reservas de Clases de Spinning** en un gimnasio. 
El proyecto abarca el diseño del modelo de negocio, el análisis de actores y la especificación formal de casos de uso estructurados bajo el paradigma Orientado a Objetos.

---

## Tabla de Contenidos
- [Descripción del Proyecto](##-descripción-del-proyecto)
- [Estructura del Repositorio](##-estructura-del-repositorio)
- [Modelado de Casos de Uso](##-modelado-de-casos-de-uso)
- [Actores del Sistema](##-actores-del-sistema)
- [Casos de Uso Principales](##-casos-de-uso-principales)
- [Visualización de Diagramas](##-visualización-de-diagramas)
- [Autor](##-autor)

---

## Descripción del Proyecto

La plataforma ofrece una solución en tiempo real para gestionar clases grupales de spinning en un gimnasio, optimizando el control de cupos limitados por la disponibilidad física de bicicletas. 

El sistema diferencia el acceso entre usuarios con membresía y clientes externos, automatiza la programación de horarios semanales, gestiona pagos y apoya al personal en el control de asistencia.

### Objetivos Clave
- **Garantizar la reserva gratuita** a afiliados con membresía activa.
- **Monetizar el acceso** de usuarios no afiliados mediante cobro individual.
- **Optimizar la capacidad** permitiendo la cancelación oportuna de reservas para liberar cupos.
- **Simplificar la logística operativa** facilitando el agendamiento y el registro de asistencia de los instructores.

---

## Estructura del Repositorio

```text
.
├── informe/
│   ├── Lab04.docx                      # CU 5: Informe técnico de laboratorio en Word
│   └── Lab04.pdf                       # Informe técnico de laboratorio en PDF
├── diagramas/
│   ├── casoDeUso_1.drawio              # CU 1: Reservar clase (Afiliado)
│   ├── casoDeUso_2.drawio              # CU 2: Reservar y pagar clase (No afiliado)
│   ├── casoDeUso_3.drawio              # CU 3: Cancelar reserva (Afiliado, No afiliado)
│   ├── casoDeUso_4.drawio              # CU 4: Gestionar horario de clases (Administrador)
│   ├── casoDeUso_5.drawio              # CU 5: Registrar asistencia (Instructor)
│   └── casoDeUso_General.drawio        # Diagrama de casos de uso general integrado
└── README.md                           # Documentación principal del repositorio
```

---

## Actores del Sistema

| Actor | Descripción |
| :--- | :--- |
| **Afiliado** | Usuario con membresía activa en el gimnasio que reserva clases de spinning sin costo adicional. |
| **No Afiliado** | Usuario externo sin membresía que reserva y paga individualmente por cada clase a la que desea asistir. |
| **Instructor** | Personal encargado de dictar la clase y registrar la asistencia real de los participantes. |
| **Administrador** | Personal responsable de programar el horario semanal, definir cupos máximos y asignar los instructores. |

---

## Casos de Uso Principales

1. **CU1: Reservar clase de spinning (Afiliado):** Permite a un usuario con membresía activa reservar un cupo en una clase programada sin costo adicional. Incluye la consulta de cupos disponibles.
2. **CU2: Reservar y pagar clase de spinning (No afiliado):** Permite a un usuario externo reservar un cupo previo pago del valor correspondiente a la clase. Incluye el proceso de pago.
3. **CU3: Cancelar reserva:** Habilita a afiliados o no afiliados a cancelar una reserva previamente confirmada dentro de los tiempos permitidos para liberar el cupo.
4. **CU4: Gestionar horario de clases:** Permite al administrador definir los horarios semanales, asignar el instructor y fijar la capacidad máxima de bicicletas por sesión.
5. **CU5: Registrar asistencia a clase:** Habilita al instructor para validar y marcar en el sistema la asistencia presencial de los participantes registrados.

---

## Visualización de Diagramas

Los diagramas arquitectónicos del modelo de negocio se encuentran guardados en formato nativo editable de **Draw.io / diagrams.net** (`.drawio`):

---

## Autor

- **David Francisco Alonso Rodríguez** — *Código: 160005001*
- Universidad de los Llanos
