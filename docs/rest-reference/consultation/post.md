---
sidebar_position: 1
---

# Method: POST Consultation Registration
Terakhir disunting pada `17 Mei 2023`

Create consultation in telemedicine.

#### HTTP request

<div class="card mb-5">
  <div class="card-body">
    POST <a href="https://api-telecare-yankes-itb.indihealth.com/api/v1/registrasi">https://api-telecare-yankes-itb.indihealth.com/api/v1/registrasi.</a>
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

```js
"body": {
	"mode": "raw",
	"raw": "{\n    \"idPasien\": 100,\n    \"idJadwal\": 10,\n    \"idFasyankes\": 12345678\n\n}",
	"options": {
	"raw": {
	"language": "json"
  	}
  }
}
```
#### Response Body
If successful, the response body empty.

