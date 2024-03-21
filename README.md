<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Club Bitches</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="tabs">
        <button class="tab-button" onclick="openTab('Welcome')">Welcome</button>
        <button class="tab-button" onclick="openTab('Schedule')">Schedule</button>
        <button class="tab-button" onclick="openTab('Members')">Members</button>
    </div>

    <div id="Welcome" class="tab-content">
        <h2>Welcome to Club Bitches</h2>
        <img src="logo.png" alt="Club Logo" class="logo">
    </div>

    <div id="Schedule" class="tab-content" style="display:none">
        <h2>Weekly Schedule</h2>
        <ul contenteditable="true">
            <li>Monday: Event 1</li>
            <li>Tuesday: Event 2</li>
            <!-- Add more days as needed -->
        </ul>
    </div>

    <div id="Members" class="tab-content" style="display:none">
        <h2>Club Members</h2>
        <div id="membersList">
            <!-- Members will be introduced here -->
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>
