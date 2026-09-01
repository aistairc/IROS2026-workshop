---
layout: schedule
title: Schedule
permalink: /schedule/
---
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Event Schedule</title>

<style>
    body {
        font-family: Arial, sans-serif;
        background-color: #f4f6f9;
        padding: 30px;
    }

    .schedule-container {
        max-width: 900px;
        margin: auto;
    }

    h1 {
        text-align: center;
        color: #333;
    }

    table {
        width: 100%;
        border-collapse: collapse;
        background: white;
        box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        border-radius: 8px;
        overflow: hidden;
    }

    th {
        background-color: #0078d4;
        color: white;
        padding: 15px;
        text-align: left;
    }

    td {
        padding: 12px 15px;
        border-bottom: 1px solid #ddd;
    }

    tr:nth-child(even) {
        background-color: #f8f9fa;
    }

    tr:hover {
        background-color: #eaf3ff;
    }

    .time {
        font-weight: bold;
        width: 20%;
    }

    .event {
        width: 50%;
    }

    .speaker {
        width: 30%;
    }
</style>
</head>
<body>

<div class="schedule-container">
    <h1>Conference Schedule</h1>

    <table>
        <thead>
            <tr>
                <th>Time</th>
                <th>Event</th>
                <th>Speaker</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td class="time">09:00 AM</td>
                <td class="event">Registration & Welcome Coffee</td>
                <td class="speaker">Event Staff</td>
            </tr>
            <tr>
                <td class="time">10:00 AM</td>
                <td class="event">Opening Remarks</td>
                <td class="speaker">John Smith</td>
            </tr>
            <tr>
                <td class="time">11:00 AM</td>
                <td class="event">Keynote Presentation</td>
                <td class="speaker">Dr. Sarah Johnson</td>
            </tr>
            <tr>
                <td class="time">12:30 PM</td>
                <td class="event">Lunch Break</td>
                <td class="speaker">-</td>
            </tr>
            <tr>
                <td class="time">02:00 PM</td>
                <td class="event">Panel Discussion</td>
                <td class="speaker">Industry Experts</td>
            </tr>
            <tr>
                <td class="time">04:00 PM</td>
                <td class="event">Closing Session</td>
                <td class="speaker">Conference Chair</td>
            </tr>
        </tbody>
    </table>
</div>

</body>
</html>
