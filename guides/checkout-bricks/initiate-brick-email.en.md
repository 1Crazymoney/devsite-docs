> CLIENT_SIDE
>
> h1
>
> Initiate Brick with e-mail

| Brick | Card Payment Brick |
| --- | --- |
| Customization moment | When rendering Brick |
| Property | initialization.payer.email |
| Type | string |
| Comments | When a valid email is sent, the email field is hidden. |

```javascript
const settings = {
   initialization: {
       amount: number,
       payer: {
           email: 'string',
       },
   },
   ...
}
```
 
> PREV_STEP_CARD_EN
>
> Change CSS variables
>
> Learn how to change the Card Payment Brick CSS variables if you need.
>
> [Change CSS variables](/developers/en/docs/checkout-bricks-beta/additional-customization/modify-css-variables)

> NEXT_STEP_CARD_EN
>
> Initiate Brick with identity document
>
> If you prefer, check how to initiate Card Payment Brick with an identity document.
>
> [Initiate Brick with identity document](/developers/en/docs/checkout-bricks-beta/additional-customization/initiate-brick-with-document)