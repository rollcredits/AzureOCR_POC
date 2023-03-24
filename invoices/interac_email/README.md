From: https://drive.google.com/file/d/1-r7ySWyK4gNJ6UXBrXRk7VoXB4HM_dgm/view?usp=sharing

![image](https://user-images.githubusercontent.com/42508203/227659122-ae51157d-5e08-4169-9cf0-7245cbde8c82.png)

### When using the prebuilt invoice model:

```json
{
  "CustomerName": {
    "kind": "string",
    "value": "N.B.",
    "content": "N.B.",
    "confidence": 0.314
  },
  "InvoiceDate": {
    "kind": "date",
    "value": {},
    "content": "Mar 3, 2023",
    "confidence": 0.613
  },
  "InvoiceId": {
    "kind": "string",
    "value": "CANf8bvh",
    "content": "CANf8bvh",
    "confidence": 0.384
  },
  "VendorAddress": {
    "kind": "address",
    "value": {
      "poBox": "P.O. Box 45",
      "city": "Toronto",
      "state": "Ontario",
      "postalCode": "M5J 2J1",
      "streetAddress": "P.O. Box 45"
    },
    "content": "P.O. Box 45, Toronto, Ontario M5J 2J1",
    "confidence": 0.597
  },
  "VendorAddressRecipient": {
    "kind": "string",
    "value": "Interac Corp.",
    "content": "Interac Corp.",
    "confidence": 0.684
  },
  "VendorName": {
    "kind": "string",
    "value": "Interac",
    "content": "Interac",
    "confidence": 0.801
  }
}
```

### When using the prebuilt *receipt* model instead (as it's more similar to a receipt):

```json
{
  "MerchantAddress": {
    "kind": "address",
    "value": {
      "poBox": "P.O. Box 45",
      "city": "Toronto",
      "state": "Ontario",
      "postalCode": "M5J 2J1",
      "streetAddress": "P.O. Box 45"
    },
    "content": "P.O. Box 45, Toronto, Ontario M5J 2J1",
    "confidence": 0.985
  },
  "MerchantName": {
    "kind": "string",
    "value": "Interac Corp.",
    "content": "Interac Corp.",
    "confidence": 0.98
  },
  "Total": {
    "kind": "number",
    "value": 45.02,
    "content": "$45.02",
    "confidence": 0.941
  },
  "TransactionDate": {
    "kind": "date",
    "value": {},
    "content": "Mar 3, 2023",
    "confidence": 0.986
  },
  "TransactionTime": {
    "kind": "time",
    "value": "05:41:00",
    "content": "5:41 AM",
    "confidence": 0.988
  }
}
```
