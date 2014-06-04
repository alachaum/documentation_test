Maestrano Documentation
=======================

Hello World
-----------

```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```
 
```python
s = "Python syntax highlighting"
print s
```
 
```
No language indicated, so no syntax highlighting. 
But let's throw in a <b>tag</b>.
```

```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

```haml
%table{ style: "width:100%" }
  %tr
    %td{ style: "width:50%" }
      %p Hello
    %td{ style: "width:50%" }
      .highlight
        =@readme_processed.html_safe
```

```json
#<Stripe::ListObject:0x3fe634d74498> JSON: {
  "object": "list",
  "count": 3,
  "url": "v1/customers",
  "data": [
    #<Stripe::Customer id=cus_49vkclzaK0Yco5 0x00000a> JSON: {
      "object": "customer",
      "created": 1401878667,
      "id": "cus_49vkclzaK0Yco5",
      "livemode": false,
      "description": "Customer for test@example.com",
      "email": null,
      "delinquent": false,
      "metadata": {
      },
      "subscriptions": {
        "object": "list",
        "total_count": 0,
        "has_more": false,
        "url": "/v1/customers/cus_49vkclzaK0Yco5/subscriptions",
        "data": [
    
        ]
      },
      "discount": null,
      "account_balance": 0,
      "currency": "usd",
      "cards": {
        "object": "list",
        "total_count": 1,
        "has_more": false,
        "url": "/v1/customers/cus_49vkclzaK0Yco5/cards",
        "data": [
          {
            "id": "card_1049vk2eZvKYlo2C2h1VAaQB",
            "object": "card",
            "last4": "4242",
            "type": "Visa",
            "exp_month": 6,
            "exp_year": 2015,
            "fingerprint": "Xt5EWLLDS7FJjR1c",
            "country": "US",
            "name": null,
            "address_line1": null,
            "address_line2": null,
            "address_city": null,
            "address_state": null,
            "address_zip": null,
            "address_country": null,
            "cvc_check": "pass",
            "address_line1_check": null,
            "address_zip_check": null,
            "customer": "cus_49vkclzaK0Yco5"
          }
        ]
      },
      "default_card": "card_1049vk2eZvKYlo2C2h1VAaQB"
    },
    #<Stripe::Customer[...] ...>,
    #<Stripe::Customer[...] ...>
  ]
}
```

Adrien
