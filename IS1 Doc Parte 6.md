---
tags:
  - IS1
---
# Apartados
- [ ] Diagrama general de arquitectura
- [ ] Def por subsistema
	- [ ] Diag casos de uso espe
	- [ ] Cass de uuso especif
	- [ ] Diagrama de actividad
	- [ ] Prototipos/ Interfaz

# Interfaces
## Login/Registro
Misma pantalla para todos ls usuarios
Si el usuario utiliza cuennta ucm, se redirige cmoo estudinte y la autenficicación se asegura a traves de la UCM.
Los Ofertantes, deberán entrar con usuaris especificamnte verificads.
Admins van a parte, listra reservada

## Pág principal (diferent dep dl usuario)
### Estudiantes
Pagina rollo immobiliaria, una barra de busqueda con filtros (cercania campus, Grados(estudiantes dee la mmisma carrera), precio, opciones accesibilidad)
Luego un gran dropdoown de "Ofertas"
Las Ofertas tendran un aspcto. 
>[!Note]
>Las ofertas no son habitacionewes asiladas,, sino modelos dentro de un blque, en la ofertta se muestra cuantas eesatn libres/del total


![[Pasted image 20251201184244.png]]

- Posibles incorporaciones
	- Comunicacion a traves de la pagina (chat)
	- Pago a  traves de la pagina (mismo servicio qu epago matricula?)
## Pag Dtallada de oferta
Ofrece ya si toda la informacion y mas fotos, video ... de la habitación
Informacion del sitio y info de contacto del propietario. Aparte de esto, igual una opcion para mandarle un correo d inteeresado directamente desde la app con correo UCM.

## Pag de Notificaciones
Pag alternativa, accesoo por barra superor boton.
Notificacines de alerta de ofertas neuvas por zona. 
Si te subscribees a un bloque de habitaciones, por cer4cania o conveniencia, notif si queda alguno nuevo libre o se va un estudiante y cede la hab.
Enn caso de denegación, si otro usuario coge el piso o cuslwuirt cosa.
Y esta visualmeente rollo correeo o Popup (con notificiacionese rollo campanita).
## Pag de Ajustes/ menu lateeral
- accesibilidad
- Idioma
- Personalizacion tema...


## Pag principal de Ofertantee
Similar a la dee estudiante, con tus ofertas rollo DashBoard. 
Panel notificaciones enetreantes y opciones para adinistrar las ofertas que trienes subidas (tanto mmodificar, eliminar o añadir habitacioonees).

Filtro por los tipos de habitacion que oferta
Y un dashbard con todas lass salas de ste tipo. Si estan ocupadas, sino, desde cuando, permanencia.. Flow base de datos.
### Notifciaciones
Ntifciaciones entrantes de estudiantres mandando oferta.Opciones del estilo de rechazar o contactar.
Psible esquema de colores:
- Verde hab libre
- Roo hab ocupada
- Ammarllo? hab pendiente de concretar si se ocupa (reservada).

# Subsistemas
Control Usario/Registro
Busqueda 
Mensajeria/Notificaciones
Base de dattos (las ofertas)
## Busqueda
### Caso Uso: Estudiante busca y solicita oferta
Login, pag prin, acceso filtros, mirar oferta, abrir descipcion oferta, contactar
### Diagrama de actividad
### Protootipo
## Notificaciones
### Ofertante acepta y gestiona ofertas
Lgin, pag dashboard, acceso nootificacioones, seleccin notificacion entrante, aceptar (see manda la forma de contacto externo), pasaria la habitacion a "Amarilloo".
### Diagrama de actividad
### Prototipo

