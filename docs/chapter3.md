# Capítulo III: Requirements Specification

## 3.1 User Stories




## 3.2 Impact Mapping

En el Impact Mapping del modelo de negocio digital de TankMaster, desarrollado por la startup PrimeFuel, el equipo elaboró el mapa partiendo de un Business Goal principal que cumple los criterios SMART: “Optimizar la gestión y distribución de combustible, alcanzando 300 empresas solicitantes activas y 100 proveedores registrados en el primer año de operación, reduciendo en un 40% los tiempos de gestión de pedidos”. A partir de esta meta se incorporaron como Actors/Personas a los User Personas previamente definidos: Carlos Ramírez (empresa solicitante) y Andrea López (proveedora de combustible). Para cada uno se identificaron los Impacts esperados, es decir, cómo se busca cambiar su comportamiento para lograr el objetivo: en el caso de Carlos, la digitalización del registro de pedidos, la reducción de la dependencia de canales informales, el seguimiento en tiempo real y una mejor toma de decisiones basada en datos; en el caso de Andrea, la centralización de pedidos, la optimización de la planificación logística, la mejora en la comunicación con clientes y el uso de métricas para el control operativo.

A partir de estos impactos se definieron los Deliverables que la plataforma TankMaster debe ofrecer para generar dichos cambios en los actores. Entre ellos se incluyen el módulo de registro y gestión de pedidos, el sistema de tracking en tiempo real, el panel de control con métricas operativas, la planificación logística automatizada, el historial de pedidos y el sistema de notificaciones y comunicación integrada. Finalmente, en la columna de User Stories se detallaron historias en formato “Como [persona] deseo [acción] para [beneficio]” (por ejemplo, registro de pedidos, consulta de estado, actualización de entregas, coordinación logística y generación de reportes), lo que permite trazar una línea clara desde los objetivos de negocio hasta las funcionalidades del sistema, asegurando la alineación entre Business Goals, Impacts, Deliverables y el desarrollo de la solución.


 <img src="../assets/chapter-3/impactMapping.png" alt="ImpactMapping de los userPersona"/>


## 3.3 Product Backlog

<table border="1" cellspacing="0" cellpadding="6">
  <thead>
    <tr>
      <th>#Orden</th>
      <th>ID</th>
      <th>Título</th>
      <th>Descripción</th>
      <th>Story Points</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>01</td>
      <td>US-01</td>
      <td>Ver sección Home</td>
      <td>Como visitante (proveedor), quiero ver una sección de inicio que resuma el valor de TankMaster para comprender rápidamente el objetivo del sistema</td>
      <td>3</td>
    </tr>
    <tr>
      <td>02</td>
      <td>US-02</td>
      <td>Ver sección About Us</td>
      <td>Como visitante de ambos segmentos, quiero conocer quiénes están detrás de TankMaster para confiar en el sistema</td>
      <td>2</td>
    </tr>
    <tr>
      <td>03</td>
      <td>US-03</td>
      <td>Ver sección How it works?</td>
      <td>Como visitante de ambos segmentos, quiero entender cómo funciona TankMaster paso a paso para evaluar si se ajusta a mis necesidades</td>
      <td>3</td>
    </tr>
    <tr>
      <td>04</td>
      <td>US-04</td>
      <td>Enviar mensaje de contacto</td>
      <td>Como visitante de ambos segmentos, quiero enviar un mensaje desde Contact Us para solicitar más información</td>
      <td>5</td>
    </tr>
    <tr>
      <td>05</td>
      <td>US-05</td>
      <td>Registrar nuevo pedido</td>
      <td>Como solicitante, quiero registrar un pedido con tipo y cantidad de combustible para que el proveedor lo procese</td>
      <td>5</td>
    </tr>
    <tr>
      <td>06</td>
      <td>US-06</td>
      <td>Consultar estado del pedido</td>
      <td>Como solicitante, quiero ver el estado de mis pedidos para saber si están aprobados, en tránsito o entregados</td>
      <td>3</td>
    </tr>
    <tr>
      <td>07</td>
      <td>US-07</td>
      <td>Confirmar recepción de pedido</td>
      <td>Como solicitante, quiero confirmar que recibí el pedido para que el proveedor lo cierre</td>
      <td>2</td>
    </tr>
    <tr>
      <td>08</td>
      <td>US-08</td>
      <td>Subir comprobante de pago</td>
      <td>Como solicitante, quiero subir el comprobante para validar el pedido ante el proveedor</td>
      <td>3</td>
    </tr>
    <tr>
      <td>09</td>
      <td>US-09</td>
      <td>Ver historial de pedidos</td>
      <td>Como solicitante, quiero ver mis pedidos anteriores para tener control sobre mi consumo</td>
      <td>3</td>
    </tr>
    <tr>
      <td>10</td>
      <td>US-10</td>
      <td>Ver pedidos pendientes</td>
      <td>Como proveedor, quiero ver todos los pedidos pendientes para analizarlos y tomar acción</td>
      <td>2</td>
    </tr>
    <tr>
      <td>11</td>
      <td>US-11</td>
      <td>Aprobar o rechazar pedido</td>
      <td>Como proveedor, quiero aceptar o rechazar pedidos según el stock disponible para evitar conflictos de distribución</td>
      <td>5</td>
    </tr>
    <tr>
      <td>12</td>
      <td>US-12</td>
      <td>Marcar pedido como despachado</td>
      <td>Como proveedor, quiero marcar cuándo un pedido sale a entrega para notificar al cliente</td>
      <td>2</td>
    </tr>
    <tr>
      <td>13</td>
      <td>US-13</td>
      <td>Cerrar pedido</td>
      <td>Como proveedor, quiero cerrar el pedido cuando el cliente confirme la entrega para finalizar el proceso</td>
      <td>3</td>
    </tr>
    <tr>
      <td>14</td>
      <td>US-14</td>
      <td>Generar reporte de ventas</td>
      <td>Como proveedor, quiero generar reportes de ventas para tener registro de operaciones realizadas</td>
      <td>3</td>
    </tr>
    <tr>
      <td>15</td>
      <td>US-15</td>
      <td>Iniciar sesión</td>
      <td>Como usuario registrado, quiero iniciar sesión con correo y contraseña para acceder a mi cuenta</td>
      <td>3</td>
    </tr>
    <tr>
      <td>16</td>
      <td>US-16</td>
      <td>Recuperar contraseña</td>
      <td>Como usuario registrado, quiero recuperar mi contraseña para volver a acceder si la olvidé</td>
      <td>3</td>
    </tr>
    <tr>
      <td>17</td>
      <td>US-17</td>
      <td>Cerrar sesión</td>
      <td>Como usuario registrado, quiero poder cerrar sesión para mantener segura mi cuenta</td>
      <td>1</td>
    </tr>
    <tr>
      <td>18</td>
      <td>US-18</td>
      <td>Ver resumen de pedidos (Solicitante)</td>
      <td>Como solicitante, quiero ver un resumen de mis pedidos para identificar cuántos están en proceso o completados</td>
      <td>5</td>
    </tr>
    <tr>
      <td>19</td>
      <td>US-19</td>
      <td>Ver resumen de pedidos (Proveedor)</td>
      <td>Como proveedor, quiero ver un resumen de pedidos gestionados y pendientes para organizar a los clientes</td>
      <td>5</td>
    </tr>
    <tr>
      <td>20</td>
      <td>US-20</td>
      <td>Asignar vehículo a pedido</td>
      <td>Como proveedor, quiero asignar un vehículo a un pedido aprobado para organizar la logística</td>
      <td>5</td>
    </tr>
    <tr>
      <td>21</td>
      <td>US-21</td>
      <td>Asignar conductor a pedido</td>
      <td>Como proveedor, quiero asignar un conductor para completar la información de despacho</td>
      <td>5</td>
    </tr>
    <tr>
      <td>22</td>
      <td>US-22</td>
      <td>Validar disponibilidad de transporte</td>
      <td>Como proveedor, quiero saber qué vehículos están disponibles antes de asignarlos para vincularlos correctamente</td>
      <td>8</td>
    </tr>
    <tr>
      <td>23</td>
      <td>US-23</td>
      <td>Ver perfil de usuario</td>
      <td>Como usuario registrado, quiero ver mis datos de perfil para revisar mi información registrada</td>
      <td>2</td>
    </tr>
    <tr>
      <td>24</td>
      <td>US-24</td>
      <td>Editar datos de perfil</td>
      <td>Como usuario registrado, quiero editar mis datos para mantener mi información actualizada</td>
      <td>3</td>
    </tr>
    <tr>
      <td>25</td>
      <td>US-25</td>
      <td>Ver sección de preguntas frecuentes</td>
      <td>Como visitante de ambos segmentos, quiero acceder a una sección de preguntas frecuentes para resolver dudas rápidamente</td>
      <td>3</td>
    </tr>
    <tr>
      <td>26</td>
      <td>US-26</td>
      <td>Acceder a información de contacto rápido</td>
      <td>Como usuario de ambos segmentos, quiero ver datos de contacto directo (teléfono o correo) para hacer consultas urgentes</td>
      <td>2</td>
    </tr>
    <tr>
      <td>27</td>
      <td>US-27</td>
      <td>Buscar pedido por código</td>
      <td>Como usuario de ambos segmentos, quiero buscar un pedido específico por su código para encontrarlo rápidamente</td>
      <td>2</td>
    </tr>
    <tr>
      <td>28</td>
      <td>US-28</td>
      <td>Filtrar pedidos por estado</td>
      <td>Como usuario de ambos segmentos, quiero filtrar mis pedidos por estado (pendiente, aprobado, entregado) para facilitar la revisión</td>
      <td>2</td>
    </tr>
    <tr>
      <td>29</td>
      <td>US-29</td>
      <td>Recibir notificación de aprobación</td>
      <td>Como solicitante, quiero recibir una notificación cuando un pedido sea aprobado o rechazado para  estar informado</td>
      <td>2</td>
    </tr>
    <tr>
      <td>30</td>
      <td>US-30</td>
      <td>Notificación de pedido despachado</td>
      <td>Como solicitante, quiero recibir una notificación cuando un pedido haya sido despachado para estar informado</td>
      <td>2</td>
    </tr>
    <tr>
      <td>31</td>
      <td>US-31</td>
      <td>Ver listado de empresas</td>
      <td>Como proveedor, quiero ver una lista de empresas solicitantes para identificar a mis clientes frecuentes</td>
      <td>3</td>
    </tr>
    <tr>
      <td>32</td>
      <td>US-32</td>
      <td>Ver detalles de empresa</td>
      <td>Como proveedor, quiero ver información detallada de una empresa solicitante para analizar su historial de pedidos</td>
      <td>3</td>
    </tr>
    <tr>
      <td>33</td>
      <td>US-33</td>
      <td>Ver gráfico de consumo (Solicitante)</td>
      <td>Como solicitante, quiero ver un gráfico de mi consumo mensual para tener control sobre el uso del combustible</td>
      <td>5</td>
    </tr>
    <tr>
      <td>34</td>
      <td>US-34</td>
      <td>Ver gráfico de ventas (Proveedor)</td>
      <td>Como proveedor, quiero ver un gráfico de ventas por mes para monitorear el rendimiento del negocio</td>
      <td>5</td>
    </tr>
    <tr>
      <td>35</td>
      <td>US-35</td>
      <td>Descargar reporte PDF</td>
      <td>Como usuario de ambos segmentos, quiero descargar un resumen de pedidos o ventas en formato PDF para archivarlo o compartirlo</td>
      <td>3</td>
    </tr>
    <tr>
      <td>36</td>
      <td>US-36</td>
      <td>Ver sección Main Suppliers</td>
      <td>Como visitante de ambos segmentos, quiero conocer los principales proveedores de combustible que trabajan con TankMaster para confiar en la plataforma</td>
      <td>1</td>
    </tr>
    <tr>
      <td>37</td>
      <td>US-37</td>
      <td>Ver sección Our Clients</td>
      <td>Como visitante de ambos segmentos, quiero conocer a las empresas que utilizan TankMaster para tener confianza en la plataforma y saber que otras empresas ya la están usando</td>
      <td>3</td>
    </tr>
    <tr>
      <td>38</td>
      <td>US-38</td>
      <td>Ver sección Are You A Fuel Requester?</td>
      <td>Como visitante (solicitante), quiero saber si cumplo con los requisitos de solicitante de combustible para poder iniciar un proceso de registro o solicitud</td>
      <td>5</td>
    </tr>
    <tr>
      <td>39</td>
      <td>US-39</td>
      <td>Cambiar idioma</td>
      <td>Como visitante de ambos segmentos, quiero poder cambiar entre inglés y español para entender la plataforma en mi idioma preferido</td>
      <td>8</td>
    </tr>
    <tr>
      <td>40</td>
      <td>US-40</td>
      <td>Registrar empresa solicitante</td>
      <td>Como visitante (solicitante), quiero registrar mi empresa en la plataforma para comenzar a realizar pedidos de combustible.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>41</td>
      <td>US-41</td>
      <td>Registrar empresa proveedora</td>
      <td>Como visitante (proveedor), quiero registrar mi empresa distribuidora en la plataforma para comenzar a gestionar pedidos de combustible.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>42</td>
      <td>US-42</td>
      <td>Rechazar pedido</td>
      <td>Como proveedor, quiero rechazar un pedido cuando no pueda atenderlo para notificar al solicitante oportunamente.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>43</td>
      <td>US-43</td>
      <td>Ver detalle de pedido</td>
      <td>Como usuario de ambos segmentos, quiero ver el detalle completo de un pedido para revisar toda la información asociada.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>44</td>
      <td>US-44</td>
      <td>Gestionar vehículos de flota</td>
      <td>Como proveedor, quiero registrar y administrar los vehículos de mi flota para tenerlos disponibles al momento de asignarlos a pedidos.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>45</td>
      <td>US-45</td>
      <td>Gestionar conductores</td>
      <td>Como proveedor, quiero registrar y administrar los conductores de mi empresa para asignarlos correctamente a los despachos.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>46</td>
      <td>US-46</td>
      <td>Ver sección Planes y Precios</td>
      <td>Como visitante de ambos segmentos, quiero conocer los planes disponibles para evaluar qué opción se adapta mejor a mi empresa.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>47</td>
      <td>US-47</td>
      <td>Ver sección Testimonios de Clientes</td>
      <td>Como visitante de ambos segmentos, quiero leer testimonios de empresas que ya usan TankMaster para generar confianza antes de registrarme.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>48</td>
      <td>US-48</td>
      <td>Cambiar idioma de la plataforma</td>
      <td>Como visitante de ambos segmentos, quiero cambiar entre español e inglés para usar la plataforma en mi idioma preferido.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>49</td>
      <td>US-49</td>
      <td>Acceder a preguntas frecuentes</td>
      <td>Como visitante de ambos segmentos, quiero consultar una sección de preguntas frecuentes para resolver dudas sin necesidad de contactar soporte.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>50</td>
      <td>US-50</td>
      <td>Ver información de contacto directo</td>
      <td>Como usuario de ambos segmentos, quiero ver los datos de contacto directo de soporte para realizar consultas urgentes.</td>
      <td>2</td>
    </tr>
  </tbody>
</table>
