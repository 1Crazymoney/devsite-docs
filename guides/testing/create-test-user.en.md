# Create test user

The testing stage allows you to analyze if the integration was successful and if the subscription acquisition is working without errors.

To perform the integration test, you will need test users that assess the operation of the integration through payment flows in an environment identical to that of the integration. 

Below we list the two types of users required to perform the tests:

* **Seller:** This is the account you use to configure the application and billing credentials.
* **Buyer:** This is the account you use to test the purchase process.

To create a test user, send a POST with your production credential Access token to the [/users/test_user](https://www.mercadopago[FAKER][URL][DOMAIN]/developers/en/reference/test_user/_users_test_user/post) endpoint and execute the request.

> NEXT_STEP_CARD_EN
>
> Making test purchase
>
> Check how to make a test purchase and validate your integration.
>
> [Making test purchase](https://www.mercadopago[FAKER][URL][DOMAIN]/developers/en/guides/testing/test-purchase)