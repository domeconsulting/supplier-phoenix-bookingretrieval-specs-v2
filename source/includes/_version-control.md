# Control de versiones

<aside class="notice">Versión actual <b>1.1.2</b></aside>

Fecha | Autor | Versión | Cambios realizados
--------- | ----------- | ----------- | ----------- 
07/04/2017 | Tomeu Roig | 1.0.0 | Especificaciones PUSH de la API Supplier-Phoenix
28/01/2019 | Rafel Mestre | 1.1.0 | Se añade el nodo PaymentDetail para el histórico de pagos de la reserva
26/04/2019 | Rafel Mestre | 1.1.1 | Se añade el campo modificationDate para las modificaciones de reserva
21/11/2019 | Rafel Mestre | 1.1.2 | Se añaden nuevos valores informativos en el nodo ExtraCustomData 
20/03/2020 | Rafel Mestre | 1.1.3 | Se añade el valor ota del método de pago. Se añade el país de orígen de la reserva.
23/03/2020 | Rafel Mestre | 1.1.3 | Se añaden los nombres de los pasajeros de la reserva.
10/06/2020 | Rafel Mestre | 1.1.4 | Se añade información adicional en los pasajeros, necesaria para efectuar el check-in
06/07/2020 | Rafel Mestre | 1.1.5 | Se añade el nombre interno de las políticas comerciales aplicadas a una reserva. Se añade también la marca de 'NoShow' a nivel de habitación, en las reservas.
10/07/2020 | Rafel Mestre | 1.1.6 | Se añaden más campos (fecha de expedición del documento, fecha de caducidad del documento y el código postal) en la información de los pasajeros.
17/07/2020 | Rafel Mestre | 1.1.7 | Se añade el importe original de la reserva en el nodo ExtraCustomData (OriginalAmount)
29/07/2020 | Rafel Mestre | 1.1.8 | Se añade el tipo de suplemento y los códigos promocionales aplicados
03/11/2020 | Rafel Mestre | 1.1.9 | Se añaden el campo 'gender' para el check-in online. Se añade el código ISO3166 en la nacionalidad.
04/11/2020 | Rafel Mestre | 1.1.10 | Se añade la comisión a nivel de reserva. También se añade el tipo de suplemento interno en la reserva.
03/02/2021 | Rafel Mestre | 1.1.11 | Se añaden los gastos de cancelación en la reserva.
10/03/2021 | Rafel Mestre | 1.1.12 | Se añade la información de los vuelos en los suplementos de transfer.
12/03/2021 | Rafel Mestre | 1.1.13 | Se añade el nuevo valor 'CostDate' en el ExtraCustomData.
09/07/2021 | Rafel Mestre | 1.1.14 | Se añade el nuevo mensaje de confirmación de reservas (BookingConfirmMessage)
09/08/2021 | Rafel Mestre | 1.1.15 | Se añaden las reglas de venta en la descarga de reservas (Esta opción se tiene que activar desde Connectivity).
08/09/2021 | Rafel Mestre | 1.1.16 | Se añaden campos a nivel de habitación y de suplemento, para la ayuda en la facturación.
17/12/2021 | Rafel Mestre | 1.1.17 | Se añade nueva información referente al cliente de la reserva.
26/01/2022 | Rafel Mestre | 1.1.18 | Se añade el parámetro 'card' en la petición de notificación de reservas por push
23/03/2022 | Rafel Mestre | 1.1.19 | Se añade el documento de identificación a la persona de contacto.
24/08/2022 | Rafel Mestre | 1.1.21 | Se añade el nuevo mensaje para añadir pagos a reservas (bookingAddPaymentMessage)
19/12/2022 | Rafel Mestre | 1.1.22 | Se cambia el tipo del id de habitación de Integer a String
09/05/2023 | Isaac Fullana | 1.1.23 | Se añade el elemento breakdown a nivel de PaymentDetail
27/06/2023 | Rafel Mestre | 1.1.24 | Se añade el elemento loyalty que identifica las reservas de tipo GENIUS de Booking.com
11/07/2023 | Rafel Mestre | 1.1.25 | Se permite la recuperación de reservas por localizador externo (clientReference).
21/07/2023 | Rafel Mestre | 1.1.26 | Se cambia el tipo del campo BookingRoomId de Integer a String
24/07/2023 | Rafel Mestre | 1.1.27 | Se añade el campo 'address' en los datos del cliente final de reserva (endCustomer).
24/01/2024 | Rafel Mestre | 1.1.28 | Se cambia el tipo del campo serviceId del nodo commission, de Integer a String.
07/03/2024 | Rafel Mestre | 1.1.29 | Se añade el elemento extraCustomData a nivel de habitación (BookingRoom).
15/05/2024 | Rafel Mestre | 1.1.30 | Se añade el elemento language (idioma) a nivel de cliente final (endCustomer).
20/08/2024 | Rafel Mestre | 1.1.31 | Nuevo mensaje de reventa de reservas (BookingResaleMessage)
20/08/2024 | Rafel Mestre | 1.1.32 | Nuevo mensaje de cancelación de reservas (BookingCancelMessage)
11/12/2024 | Rafel Mestre | 1.1.33 | Envío de las etiquetas asignadas a la persona de contacto de la reserva
09/04/2025 | Rafel Mestre | 1.1.34 | Actualización de ejemplos de reserva (BookingRetrievalResponse).
09/04/2025 | Rafel Mestre | 1.1.35 | Actualización de los valores devueltos en el campo ExtraCustomData.