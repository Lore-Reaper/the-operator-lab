# The Operator Lab 🖥️

> *"La mejor forma que conozco de aprender administración de sistemas es montar algo, romperlo y volver a empezar."*

¡Buenas!

Si has llegado hasta aquí, seguramente estés curioseando mi GitHub. Este repositorio es mi laboratorio personal. Lo empecé después de terminar ASIR porque me di cuenta de que muchas de las prácticas que hacía acababan perdidas en una máquina virtual o en un disco duro.

Aquí quiero hacer justo lo contrario.

La idea es ir construyendo un servidor desde cero, documentando todo lo que hago: lo que sale bien, lo que sale mal y las decisiones que voy tomando por el camino.

No busco montar una infraestructura enorme ni aparentar que trabajo en un CPD de una multinacional. Lo que quiero es aprender haciendo las cosas con calma y entender por qué funcionan.

Si dentro de un año vuelvo a este repositorio, me gustaría que me sirviera como un cuaderno de trabajo.

---

## ¿Qué voy a montar?

De momento, esto es lo que tengo pensado:

- Ubuntu Server 24.04 LTS como sistema principal.
- Docker para levantar servicios sin complicarme demasiado.
- Portainer para gestionar los contenedores.
- UFW y Fail2Ban para reforzar un poco la seguridad.
- Scripts en Bash para automatizar tareas repetitivas.
- Copias de seguridad con `rsync`.
- Monitorización básica para controlar el estado del servidor.

Seguramente la lista cambie con el tiempo. Si descubro una herramienta interesante, la añadiré.

---

## Objetivos personales

No quiero aprender comandos de memoria.

Quiero entender qué hacen.

No quiero copiar tutoriales.

Quiero ser capaz de montar un servidor sin depender de ellos.

Y, sobre todo, quiero acostumbrarme a documentar lo que hago, porque es una parte del trabajo que muchas veces se deja de lado.

---

## Estado del proyecto

🟢 En construcción.

Acabo de empezar, así que esto irá cambiando bastante.

---

## Estructura

```
the-operator-lab/

├── docs/
├── scripts/
├── docker/
├── images/
├── logs/
├── backups/
└── README.md
```

---

## Licencia

MIT

---

Gracias por pasarte por aquí.
