# feb-2025-avasjcript-events-and-basic-interactivity
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mouseover Event Example</title>
    <style>
        #hoverElement {
            width: 200px;
            height: 100px;
            background-color: lightblue;
            text-align: center;
            line-height: 100px;
            font-size: 18px;
        }
    </style>
</head>
<body>
    <div id="hoverElement">Hover Over Me!</div>

    <script>
        const hoverElement = document.getElementById('hoverElement');

        hoverElement.addEventListener('mouseover', function() {
            hoverElement.style.backgroundColor = 'lightgreen';
            hoverElement.textContent = 'You hovered over me!';
        });

        hoverElement.addEventListener('mouseout', function() {
            hoverElement.style.backgroundColor = 'lightblue';
            hoverElement.textContent = 'Hover Over Me!';
        });
    </script>
</body>
</html>
