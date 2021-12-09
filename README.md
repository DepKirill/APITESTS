{
  "checkout": {
    "test": true,
    "transaction_type": "payment",
    "attempts": 3,
    "settings": {
      "return_url": "http://127.0.0.1:4567/return",
      "success_url": "http://127.0.0.1:4567/success",
      "decline_url": "http://127.0.0.1:4567/decline",
      "fail_url": "http://127.0.0.1:4567/fail",
      "cancel_url": "http://127.0.0.1:4567/cancel",
      "notification_url": "http://your_shop.com/notification",
      "button_text": "Привязать карту",
      "button_next_text": "Вернуться в магазин",
      "language": "en",
      "customer_fields": {
        "visible": ["first_name", "last_name"],
        "read_only": ["email"]
      },
      "credit_card_fields": {
        "holder": "Rick Astley",
        "read_only": ["holder"]
      }
    },
    "order": {
      "currency": "GBP",
      "amount": 4299,
      "description": "Order description"
    },
    "customer": {
      "address": "Baker street 221b",
      "country": "GB",
      "city": "London",
      "email": "jake@example.com"
    }
  }
}
