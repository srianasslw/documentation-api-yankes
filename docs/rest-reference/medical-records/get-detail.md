---
sidebar_position: 1
---

# Method: GET Medical Records Detail
Terakhir disunting pada `17 Mei 2023`

Gets information about Consultation.

#### HTTP request

<div class="card mb-5">
  <div class="card-body">
    GET <a href="http://localhost:8000/api/v1/rekam-medik/25?idPasien=667">http://localhost:8000/api/v1/rekam-medik/25?idPasien=667.</a>
  </div>
</div>

#### Authorization Scopes

```js
"header": [
  {
    "key": "Authorization",
    "value": "056ac848d188836d9d68cec96ef68cfe7f2d5873-d4b118c1-067e-4799-8feb-11829affb353",
    "type": "text"
  }
]
```
#### Request Body
The request body must be empty.

#### Query

```js
"query": [
	{
		"key": "idPasien",
		"value": "667"
	}
]
```
#### Response Body
If successful, the response body empty.

