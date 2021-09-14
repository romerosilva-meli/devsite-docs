# Activating production mode

The first step to activate production mode in your store is to **enable the SSL certificate** on your domain. This certificate is used to increase the security of the data shared by your store, in other words, your customers' personal information.

Many hosting services offer, along with the domain, the SSL certificate. If your domain does not have this certificate, we recommend looking for a company that can help you with the purchase and installation. 

For more information, check our documentation [Requirements for the production environment](https://www.mercadopago[FAKER][URL][DOMAIN]/developers/en/guides/online-payments/checkout-api/goto-production).

With the certificate activated and testing completed, you can toggle your store out of Test mode and enable the **Production** environment. This will allow you to make actual sales.

Follow the steps below to make the change:

1. Access your WordPress Panel.
2. In the left side bar, click on **WooCommerce** **> Settings**.
3. In **Payments**, search for the checkout you chose in step **Integration setup**, and click on **Manage**.
4. In _Add credentials to "Test Mode"or "Production Mode"_, choose _Activate Production Mode for Mercado Pago checkouts_. 
5. Click on _Salvar alterações_.

Done! Your store is in Production environment and ready to process your sales.

> LEFT_BUTTON_REQUIRED_EN
>
> Sales processing
>
> Learn the main statuses during sales processing.
>
> [Sales processing](https://www.mercadopago[FAKER][URL][DOMAIN]/developers/en/guides/plugins/woocommerce/sales-processing)