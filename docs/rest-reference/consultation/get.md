---
sidebar_position: 2
---

# Method: GET Consultation Schedule
Terakhir disunting pada `17 Mei 2023`

Gets information about Consultation.

#### HTTP request

<div class="card mb-5">
  <div class="card-body">
    GET <a href="http://localhost:8000/api/v1/jadwal-konsultasi?idPasien=641">http://localhost:8000/api/v1/jadwal-konsultasi?idPasien=641.</a>
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
		"value": "641"
	}
]
```
#### Response Body
If successful, the response body empty.

