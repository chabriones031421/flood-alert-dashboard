# flood-alert-dashboard
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Metro Manila & Nearby Provinces: Flood & Weather Advisory</title>
  <meta http-equiv="refresh" content="3600" />
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f3f7fa;
      color: #333;
      margin: 0;
      padding: 1rem;
    }
    h1 {
      text-align: center;
      color: #005288;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 1rem;
      margin-top: 2rem;
    }
    .card {
      background: white;
      border-radius: 8px;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
      padding: 1rem;
    }
    .card a {
      color: #007acc;
      font-weight: bold;
      text-decoration: none;
    }
    .card a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <h1>🌧️ Flood & Weather Advisory Dashboard</h1>
  <p style="text-align:center;">Auto-refreshes every hour • Source: Official Facebook Pages</p>
  <div class="grid">
    <div class="card"><strong>Manila:</strong><br><a href="https://www.facebook.com/ManilaPIO" target="_blank">Manila PIO</a></div>
    <div class="card"><strong>Pasig:</strong><br><a href="https://www.facebook.com/PasigCityDRRMO" target="_blank">Pasig City DRRMO</a></div>
    <div class="card"><strong>Makati:</strong><br><a href="https://www.facebook.com/makatidrrmoffice1" target="_blank">Makati DRRM Office</a></div>
    <div class="card"><strong>Valenzuela:</strong><br><a href="https://www.facebook.com/ValenzuelaCityGov" target="_blank">Valenzuela City Gov</a></div>
    <div class="card"><strong>Taguig:</strong><br><a href="https://www.facebook.com/taguigPIO" target="_blank">Taguig PIO</a></div>
    <div class="card"><strong>Pasay:</strong><br><a href="https://www.facebook.com/lgupasaypio" target="_blank">Pasay PIO</a></div>
    <div class="card"><strong>Parañaque:</strong><br><a href="https://www.facebook.com/CityOfParanaqueOfficial" target="_blank">Parañaque City Official</a></div>
    <div class="card"><strong>Muntinlupa:</strong><br><a href="https://www.facebook.com/OspitalNgMuntinlupaOfficial" target="_blank">Ospital ng Muntinlupa</a></div>
    <div class="card"><strong>Marikina:</strong><br><a h
