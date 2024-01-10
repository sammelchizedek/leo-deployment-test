# leo-deployment-test
<!DOCTYPE html>
<html>
<head>
    <title>PHP Front End Page</title>
</head>
<body>
    <?php
    // Display a welcome message
    echo "<h1>Welcome to my website!</h1>";

    // Display the current date and time
    date_default_timezone_set("Asia/Kolkata"); // Set the default timezone
    echo "<p>Today is " . date("l, d F Y") . "</p>"; // Display the date
    echo "<p>The current time is " . date("h:i:s A") . "</p>"; // Display the time
    ?>
</body>
</html>
