## 3.2. Architecture Overview
### 3.2.1. Domain-Driven Software Architecture
A continuación se visualizarán los diagramas C4.
#### 3.2.1.1. Software Architecture Context Level Diagram
Se puede visualizar el diagrama de contexto que representa un panorama general de la comunicación entre nuestros segmentos objetivo y la aplicación.

![contextDiagram](assets/c4/contextDiagram.png)
#### 3.2.1.2. Software Architecture Container Level Diagram
En este diagrama se puede apreciar el funcionamiento que tendrá la aplicación y las relaciones con los bounded context correspondientes, se busca organizarlos de tal forma que no generen dependencias fuertes que perjudiquen migraciones a future.

![containerDiagram](assets/c4/containerDiagramA.png)
#### 3.2.1.3. Software Architecture Components Diagram
En este diagrama se presenta de forma detallada las conexiones entre controllers, services y repositories de las entidades que contiene el bounded context.

<p style="text-align: center;"><strong>User Context</strong></p>

![componentDiagram](assets/c4/component-1.png)

<p style="text-align: center;"><strong>Subscription Context</strong></p>

![componentDiagram](assets/c4/component-2.png)

<p style="text-align: center;"><strong>Space Context</strong></p>

![componentDiagram](assets/c4/component-3.png)

<p style="text-align: center;"><strong>CreateReservation Context</strong></p>

![componentDiagram](assets/c4/component-4.png)

<p style="text-align: center;"><strong>Reservations Context</strong></p>

![componentDiagram](assets/c4/component-5.png)
### 3.2.2. Software Object-Oriented Design
#### 3.2.2.1. Class Diagrams
![diagramClass](assets/c4/AlquilaFacilDiagram.png)
#### 3.2.2.2. Class Dictionary
<table style="text-aling:center">
    <thead>
        <tr>
            <th>Clase</th>
            <th>Descripción</th>
        </tr>
    </thead>
    <body>
        <tr>
            <td> 
            <img src="assets/c4/userC.png" alt="userClass" height="200" width="200">
            </td>
            <td>Es la clase padre de las clases Organizer y Owner, es la encargada de almacenas los datos del usuario</td>
        </tr>
        <tr>
            <td> 
            <img src="assets/c4/ownerC.png" alt ="ownerC" height="120">
            </td>
            <td>La clase Owner hereda de la clase User. Representa a los propietarios de los espacios que pueden ser alquilados para eventos.</td>
        </tr>
        <tr>
            <td> 
            <img src="assets/c4/organizerC.png" alt ="organizerC" height="120">
            </td>
            <td>La clase Organizer hereda de la clase User. Representa a los organizadores de eventos que buscan y reservan espacios para sus eventos.</td>
        </tr>
        <tr>
            <td> 
            <img src="assets/c4/reservationC.png" alt ="reservationC" height="200" width="200">
            </td>
            <td>Gestiona las reservas realizadas por organizadores para espacios de eventos específicos.</td>
        </tr>
        <tr>
            <td> 
            <img src="assets/c4/eventSpaceC.png" alt ="eventSpaceC" height="200" width="200">
            </td>
            <td>Representa los espacios físicos disponibles para alquiler. Proporciona información detallada sobre el espacio, como ubicación, capacidad y características.</td>
        </tr>
        <tr>
            <td> 
            <img src="assets/c4/paymentsC.png" alt ="paymentsC" height="200" width="200">
            </td>
            <td>Representa los pagos asociados a las reservas de espacios de evento. Registra información sobre el monto, la fecha y el estado de los pagos realizados.</td>
        </tr>
        <tr>
            <td> 
            <img src="assets/c4/subscriptionC.png" alt ="subscriptionC" height="200" width="200">
            </td>
            <td>Representa las suscripciones de los propietarios a planes de servicio que ofrecen beneficios adicionales.</td>
        </tr>
        <tr>
            <td> 
            <img src="assets/c4/plansC.png" alt ="plansC" height="200" width="200">
            </td>
            <td>Define los diferentes niveles de suscripción disponibles para los propietarios de espacios.</td>
        </tr>
    </body>
</table>    

#### 3.2.2.3. Database Design

#### 3.2.2.4. Database Diagram
![dataBaseDiagram](assets/c4/db-alquilaf.jpg)


## [Conclusiones](#conclusiones)
## [Bibliografía](#bibliografía)
## [Anexos](#anexos)


