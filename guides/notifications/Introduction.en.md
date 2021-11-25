# Notifications

Notifications are responses given by the server from transactions (events) performed on its platform, these events being any type of update in the reported object, including status or attribute changes. With the notifications you will have a real-time information about the changes produced in the different resources of the Mercado Pago APIs.
 
See below the types of notifications available for integration with Mercado Pago.

> WARNING
>
> Important
>
> It is not possible to receive notifications in test/sandbox environment.

## Webhook

The [Webhook](https://www.mercadopago[FAKER][URL][DOMAIN]/developers/en/guides/notifications/webhooks) (also known as web callback or `HTTP POST`) is a simple method which makes it easy for an app or system to provide information in real time whenever an event happens, that is, it is a way of passively receiving data between two systems. This allows simple and independent programs to be created exclusively with the intention of working in a chain as other commands are executed, and it can be configured for one or more applications created in your [Dashboard](https://www.mercadopago[FAKER][URL][DOMAIN]/developers/en/guides/resources/devpanel).

Once installed, the Webhook will be sent every time one or more signed events occur, avoiding a search job every minute in search of an answer and, consequently, preventing system overload and data loss. whenever any situation occurs.

## IPN

The [IPN](https://www.mercadopago[FAKER][URL][DOMAIN]/developers/en/guides/notifications/ipn) (_Instant Payment Notification_) is a mechanism that allows your store to receive notifications from a server Mercado Pago informing the status of a certain payment, through a call `HTTP POST` to inform about its transactions. Unlike Webhook, IPN notifications can be configured for a single application at a time.