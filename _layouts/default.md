<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>{{ page.title | default: "NOUS | Classical Orthodox Christian Education" }}</title>
    
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Merriweather:wght@400;700&family=Inter:wght@400;500;700&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Inter', sans-serif; }
        .font-serif { font-family: 'Merriweather', serif; }
        .grid img { display: block; width: 100%; height: auto; margin: 0; }
    </style>
</head>
<body class="min-h-screen bg-[#FAFAFA] text-gray-800">

    {% include header.html %}

    <main>
        {{ content }}
    </main>

    {% include footer.html %}

</body>
</html>