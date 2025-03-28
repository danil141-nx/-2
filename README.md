<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Моё расписание</title>
    <style>
        body {
            background: linear-gradient(135deg, #1e5799, #2989d8);
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            color: white;
            margin: 0;
            padding: 20px;
            min-height: 100vh;
        }
        
        .container {
            background-color: rgba(255, 255, 255, 0.15);
            backdrop-filter: blur(10px);
            max-width: 800px;
            margin: 30px auto;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 8px 32px rgba(0, 0, 0, 0.3);
            border: 1px solid rgba(255, 255, 255, 0.18);
        }
        
        h1 {
            text-align: center;
            color: #fff;
            margin-bottom: 30px;
            font-size: 2.2em;
        }
        
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 25px 0;
        }
        
        th {
            background-color: rgba(255, 255, 255, 0.25);
            padding: 15px;
            text-align: center;
            font-size: 1.1em;
        }
        
        td {
            padding: 12px;
            text-align: center;
            border-bottom: 1px solid rgba(255, 255, 255, 0.1);
        }
        
        tr:nth-child(even) {
            background-color: rgba(255, 255, 255, 0.05);
        }
        
        tr:hover {
            background-color: rgba(255, 255, 255, 0.15);
            transition: background-color 0.3s;
        }
        
        .weekend {
            color: #ffcc00;
            font-weight: bold;
        }
        
        footer {
            text-align: center;
            margin-top: 40px;
            color: rgba(255, 255, 255, 0.7);
            font-size: 0.9em;
        }
        
        @media (max-width: 600px) {
            .container {
                padding: 15px;
                margin: 15px;
            }
            
            table {
                font-size: 0.9em;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>📚 Моё учебное расписание</h1>
        
        <table>
            <tr>
                <th>День</th>
                <th>Предмет</th>
                <th>Время</th>
            </tr>
            <tr>
                <td>Понедельник</td>
                <td>Математика</td>
                <td>9:00 - 10:30</td>
            </tr>
            <tr>
                <td>Вторник</td>
                <td>Физика</td>
                <td>10:45 - 12:15</td>
            </tr>
            <tr>
                <td>Среда</td>
                <td>История</td>
                <td>13:00 - 14:30</td>
            </tr>
            <tr>
                <td>Четверг</td>
                <td>Химия</td>
                <td>9:00 - 10:30</td>
            </tr>
            <tr>
                <td>Пятница</td>
                <td>Информатика</td>
                <td>10:45 - 12:15</td>
            </tr>
            <tr>
                <td>Суббота</td>
                <td>Литература</td>
                <td>13:00 - 14:30</td>
            </tr>
            <tr class="weekend">
                <td>Воскресенье</td>
                <td colspan="2">Выходной 🎉</td>
            </tr>
        </table>
        
        <footer>
            Расписание на 2023/2024 учебный год | Обновлено: сентябрь 2023
        </footer>
    </div>
</body>
</html>
