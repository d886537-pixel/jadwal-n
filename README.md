<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jadwal Pelajaran</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f4f7f6;
            display: flex;
            justify-content: center;
            padding: 20px;
        }

        .container {
            width: 100%;
            max-width: 900px;
            background: white;
            padding: 20px;
            border-radius: 12px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
        }

        h2 {
            text-align: center;
            color: #2c3e50;
            margin-bottom: 20px;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            overflow: hidden;
            border-radius: 8px;
        }

        th {
            background-color: #3498db;
            color: white;
            padding: 15px;
            text-align: left;
        }

        td {
            padding: 12px 15px;
            border-bottom: 1px solid #eee;
            color: #333;
        }

        tr:nth-child(even) {
            background-color: #f9f9f9;
        }

        tr:hover {
            background-color: #f1f1f1;
            transition: 0.3s;
        }

        .jam {
            font-weight: bold;
            color: #7f8c8d;
            width: 120px;
        }

        @media (max-width: 600px) {
            table {
                font-size: 14px;
            }
            .jam {
                width: 80px;
            }
        }
    </style>
</head>
<body>

<div class="container">
    <h2>📅 Jadwal Pelajaran</h2>
    <table>
        <thead>
            <tr>
                <th>Jam</th>
                <th>Senin</th>
                <th>Selasa</th>
                <th>Rabu</th>
                <th>Kamis</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td class="jam">07:00 - 08:30</td>
                <td>Matematika</td>
                <td>Bahasa Inggris</td>
                <td>Fisika</td>
                <td>Biologi</td>
            </tr>
            <tr>
                <td class="jam">08:30 - 10:00</td>
                <td>Bahasa Indonesia</td>
                <td>Sejarah</td>
                <td>Kimia</td>
                <td>Ekonomi</td>
            </tr>
            <tr>
                <td class="jam">10:00 - 10:30</td>
                <td colspan="4" style="text-align: center; background: #eee; font-style: italic;">Istirahat</td>
            </tr>
            <tr>
                <td class="jam">10:30 - 12:00</td>
                <td>Seni Budaya</td>
                <td>Olahraga</td>
                <td>Geografi</td>
                <td>Sosiologi</td>
            </tr>
        </tbody>
    </table>
</div>

</body>
</html>
