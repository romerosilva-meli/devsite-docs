# Configura planes de pago

Los **planes pago** son los métodos de pago que se muestran en el sitio web para la finalización de la compra. Permiten la configuración de cuotas, intereses, condiciones especiales, etc.

Luego de haber creado tu afiliación con **MercadoPagoV2**, debes configurar los **planes de pago** que se ofrecerán a los compradores.

> WARNING
>
> Importante
>
> Verifica en tu tienda de aplicaciones VTEX que la App **Mercado Pago Payment APP** este instalada para usar las condiciones de pago **MercadoPagoPro, MercadoPagoWallet y MercadoPagoOff** o solicita la instalación por parte del equipo de VTEX a través de un ticket en [Support VTEX](https://help.vtex.com/es/support).

La configuración de los planes de pago se realiza en el portal de administración de la plataforma VTEX en la pestaña **Planes de pago** del menú **Configuración** del módulo de **Pagos**.

En esta pestaña, debes hacer clic en el botón "+" (*Agregar nuevo plan de pago para ...*) y seleccionar un plan de pago.

En la pantalla siguiente, debes escribir el **Nombre de la Regla** para identificarla fácilmente, activar la condición de pago desde el campo `Status`, seleccionar **MercadoPagoV2** en la lista que ofrece el campo `Proceso con la afiliación` y, finalmente, guardar tus cambios haciendo clic en `Salva`.

Para obtener más información sobre cómo configurar los términos de pago en VTEX, haz clic [aquí](https://help.vtex.com/es/tutorial/condicoes-de-pagamento--tutorials_455).

![Configurar planes de pago](/images/vtex/paymentconditions-es.gif)

La integración con Mercado Pago te permite configurar las siguientes condiciones de pago:



|Plan de pago|Sección en la pestaña Planes de Pago|
|---|---|
|Tarjeta de Crédito|Tarjeta de Crédito|
|Tarjeta de Débito|Tarjeta de Débito|
|MercadoPagoOff|Otro|
|MercadoPagoWallet|Otro|
|MercadoPagoPro|Otro|
----[mlb]----|Boleto Bancário|Boleto|
|PIX|Pago Instantáneo|------------

También puedes configurar **condiciones especiales** de pago. Haz clic [aquí](https://help.vtex.com/es/tutorial/condicoes-especiais--tutorials_456?&utm_source=admin) para obtener más información.

Para finalizar la configuración, haz clic en **Salva**.


> NOTE
>
> NOTA
> 
> Los cambios en las Condiciones de pago pueden demorar hasta 10 minutos en aplicarse.

&nbsp;

## Configuración de Checkout Mercado Pago

Configura esta solución para cobrar a través de **Mercado Pago**, utilizando todos los métodos de pago disponibles en la plataforma.

Si configuras **MercadoPagoPro**, el comprador pagará en el entorno de Mercado Pago a través del formulario web modal directamente en tu tienda.

Si configuras **MercadoPagoWallet**, el comprador completa el pago con la billetera de Mercado Pago exclusivamente para usuarios registrados y una vez finalizado el proceso, regresará a tu tienda.

Se configura siguiendo los mismos pasos comunes a otras condiciones de pago.

&nbsp;

## Configuración de tarjeta de crédito

Configurar planes de pago con **tarjeta de crédito** requiere que [selecciones la marca de tarjeta de crédito](https://www.mercadopago[FAKER][URL][DOMAIN]/developers/es/guides/plugins/unofficial/vtex/payment-methods) que deseas agregar. Además, su configuración puede requerir que completes campos adicionales a los presentados anteriormente, dependiendo de si seleccionas **A Vista** o **En Cuotas**.

Para obtener más información sobre cómo configurar las cuotas en VTEX, haz clic [aquí](https://help.vtex.com/es/tutorial/condicoes-de-pagamento--tutorials_455#parcelado-sem-juros).

![Configuración de tarjeta de crédito](/images/vtex/paymentconditions-cc-es.gif)

&nbsp;

----[mlb]----

## Configuración de Pix

Para configurar PIX en tu integración con Mercado Pago es necesario que tu clave PIX esté configurada.

Para obtener más información sobre cómo crear tu clave PIX, haz clic [aquí](https://www.mercadopago[FAKER][URL][DOMAIN]/stop/pix?url=https%3A%2F%2Fwww.mercadopago.com.br%2Fadmin-pix-keys%2Fmy-keys&authentication_mode=required).

Si ya tienes tu clave PIX, el proceso sigue los pasos comunes a los otros planes de pago.

&nbsp;

------------

> LEFT_BUTTON_REQUIRED_ES
>
> Device Fingerprint
>
> Aprende a configurar fingerprint.
>
> [Device Fingerprint](https://www.mercadopago[FAKER][URL][DOMAIN]/developers/es/guides/plugins/unofficial/vtex/device-fingerprint)