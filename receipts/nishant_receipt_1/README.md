```json
{
  "MerchantAddress": {
    "kind": "address",
    "value": {
      "houseNumber": "500",
      "road": "World Way",
      "city": "Los Angeles",
      "state": "CA",
      "postalCode": "90045",
      "streetAddress": "500 World Way"
    },
    "content": "500 World Way\nLos Angeles, CA\n90045",
    "confidence": 0.984
  },
  "MerchantName": {
    "kind": "string",
    "value": "Lemonade LAX",
    "content": "Lemonade LAX",
    "confidence": 0.95
  },
  "Subtotal": {
    "kind": "number",
    "value": 15.23,
    "content": "$15.23",
    "confidence": 0.986
  },
  "TaxDetails": {
    "kind": "array",
    "values": {
      "0": {
        "kind": "object",
        "properties": {
          "Amount": {
            "kind": "currency",
            "value": {
              "amount": 1.45,
              "currencySymbol": "$"
            },
            "content": "$1.45",
            "confidence": 0.975
          }
        },
        "content": "Sales Tax\n$1.45",
        "confidence": 0.986
      }
    }
  },
  "Total": {
    "kind": "number",
    "value": 16.68,
    "content": "$16.68",
    "confidence": 0.975
  },
  "TransactionDate": {
    "kind": "date",
    "value": {},
    "content": "January 6, 2023",
    "confidence": 0.985
  },
  "TransactionTime": {
    "kind": "time",
    "value": "09:31:00",
    "content": "9:31 AM",
    "confidence": 0.988
  }
}
```