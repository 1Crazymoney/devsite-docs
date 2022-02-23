## Criar cancelamento

Cancelar uma compra de um pagamento específico.

[[[
```ruby
sdk = Mercadopago::SDK.new('YOUR_ACCESS_TOKEN')
 
payment_data = {
   "status": "cancelled"
}
payment = sdk.payment.update("payment_id", payment_data)

```
]]]