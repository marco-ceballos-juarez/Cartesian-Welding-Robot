# System architecture / Arquitectura del sistema

**Status / Estado:** Template / Plantilla

## System overview / Visión general

Insert the approved system block diagram and describe the main data, command, and power flows.

Insertar el diagrama de bloques aprobado y describir los principales flujos de datos, comandos y alimentación.

## Subsystems / Subsistemas

| Subsystem / Subsistema | Responsibilities / Responsabilidades | Interfaces / Interfaces |
|---|---|---|
| Mechanical / Mecánico | Structure, axes and torch fixture / Estructura, ejes y sujeción | Mechanical interfaces |
| Actuation / Accionamiento | Motors and drives / Motores y controladores | Electrical and command interfaces |
| Electronics / Electrónica | Power, wiring and communication / Alimentación, cableado y comunicación | Electrical/data |
| Motion software / Software de movimiento | Coordinate processing and motion commands / Procesamiento de coordenadas y comandos | Software/API |
| Command interpreter / Intérprete | Parse and dispatch motion program commands / Interpretar y despachar instrucciones | Text command interface |
| GUI / Interfaz | Operator interaction / Interacción con el operador | User and software interface |
| Welding equipment / Equipo de soldadura | Welding process equipment / Equipo del proceso | Process interface |

## Interface control document / Documento de control de interfaces

For every interface, record connector or protocol, signal direction, voltage or data format, units, update rate if relevant, and fault behavior.

Para cada interfaz, registrar conector o protocolo, dirección de señal, tensión o formato de datos, unidades, frecuencia de actualización si aplica y comportamiento ante fallas.

## Diagrams / Diagramas

- [ ] System block diagram / Diagrama de bloques.
- [ ] Electrical architecture / Arquitectura eléctrica.
- [ ] Software architecture / Arquitectura de software.
- [ ] Command and data flow / Flujo de comandos y datos.
