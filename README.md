<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GIF Rows</title>
    <style>
        .gif-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 10px; /* Space between GIFs */
        }
        .gif-item {
            width: 100px; /* Set the width of each GIF */
            height: 100px; /* Set the height of each GIF */
            background-image: url('https://github.com/dumbbutt0/dumbbutt0/blob/main/dead.gif?raw=true');
            background-size: cover;
            background-repeat: no-repeat;
            animation: shrink-x 0.5s linear infinite alternate;
        }
        @keyframes shrink-x {
            from {
                transform: scaleX(1);
            }
            to {
                transform: scaleX(0.5);
            }
        }
    </style>
</head>
<body>
    <div class="gif-container">
        <div class="gif-item"></div>
        <div class="gif-item"></div>
        <div class="gif-item"></div>
        <div class="gif-item"></div>
        <div class="gif-item"></div>
        <!-- Add more .gif-item divs as needed -->
    </div>
</body>
</html>
