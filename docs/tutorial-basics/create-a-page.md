---
sidebar_position: 1
---

# Endpoint Information
Terakhir disunting pada `17 Mei 2023`

Indihealth menyediakan beberapa API pada klien yang dapat membantu Anda saat membangun situs Anda.
Berikut ini daftar endpoint API untuk **INTEGRASI TELEMEDICINE** environment development, staging, dan production:

:::info

Some **API** with _Domain_ `http://api-telecare-yankes-itb.indihealth.com`. Check [this `api`](http://api-telecare-yankes-itb.indihealth.com).

:::

## Development
Berikut ini endpoint API development untuk autentifikasi, transaksi data terkait resources Konsultasi Telemedicine:

<table>
  <thead></thead>
  <tbody>
    <tr><td>Belum ada data</td></tr>
  </tbody>
</table>

## Staging
Berikut ini endpoint API staging untuk autentifikasi, transaksi data terkait resources Konsultasi Telemedicine:

<table>
  <thead></thead>
  <tbody>
    <tr><td>Belum ada data</td></tr>
  </tbody>
</table>

## Production
Berikut ini endpoint API production untuk autentifikasi, transaksi data terkait resources Konsultasi Telemedicine:

<table>
  <thead></thead>
  <tbody>
    <tr>
      <th>Pendaftaran Konsultasi</th>
      <td><a href="http://localhost:8000/api/v1/registrasi">http://localhost:8000/api/v1/registrasi</a></td>
    </tr>
    <tr>
      <th>List Jadwal Konsultasi</th>
      <td><a href="http://localhost:8000/api/v1/jadwal-konsultasi?idPasien=641">http://localhost:8000/api/v1/jadwal-konsultasi?idPasien=641</a></td>
    </tr>
    <tr>
      <th>List Jadwal Dokter</th>
      <td><a href="http://localhost:8000/api/v1/jadwal-dokter/list">http://localhost:8000/api/v1/jadwal-dokter/list</a></td>
    </tr>
    <tr>
      <th>Get Rekam Medik Detail</th>
      <td><a href="http://localhost:8000/api/v1/rekam-medik/25?idPasien=667">http://localhost:8000/api/v1/rekam-medik/25?idPasien=667</a></td>
    </tr>
    <tr>
      <th>Get List Rekam Medik</th>
      <td><a href="http://localhost:8000/api/v1/rekam-medik?idPasien=667">http://localhost:8000/api/v1/rekam-medik?idPasien=667</a></td>
    </tr>
  </tbody>
</table>

## Create your first React Page

Create a file at `src/pages/my-react-page.js`:

```jsx title="src/pages/my-react-page.js"
import React from 'react';
import Layout from '@theme/Layout';

export default function MyReactPage() {
  return (
    <Layout>
      <h1>My React page</h1>
      <p>This is a React page</p>
    </Layout>
  );
}
```

A new page is now available at [http://localhost:3000/my-react-page](http://localhost:3000/my-react-page).

## Create your first Markdown Page

Create a file at `src/pages/my-markdown-page.md`:

```mdx title="src/pages/my-markdown-page.md"
# My Markdown page

This is a Markdown page
```

A new page is now available at [http://localhost:3000/my-markdown-page](http://localhost:3000/my-markdown-page).
