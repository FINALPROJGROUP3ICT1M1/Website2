# Website2
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Proverbs 16:3</title>
    <style>
        body {
            background-color: pink;
            font-family: Arial, sans-serif;
            text-align: center;
            padding: 20px;
        }
        p {
            font-size: 24px;
            margin-bottom: 20px;
        }
        #cat-container {
            margin-top: 20px;
        }
        #cat-image {
            width: 300px; /* Adjusted size for better text visibility */
            height: auto;
            border-radius: 10px; /* Optional: slight rounding */
        }
    </style>
</head>
<body>
    <h1>Proverbs 16:3</h1>
    <p>Commit to the Lord whatever you do, and he will establish your plans.</p>
    
    <div id="cat-container">
        <img id="cat-image" src="" alt="Cute Cat Saying a Bible Verse">
    </div>

    <script>
        // Array of random Bible verses (shortened for cat API)
        var verses = [
            "God loves you ❤️",
            "Trust in the Lord - Proverbs 3:5",
            "I know the plans I have for you - Jeremiah 29:11",
            "Be strong and courageous - Joshua 1:9",
            "The Lord is my shepherd - Psalm 23:1",
            "Love your neighbor - Matthew 22:39"
        ];

        // Function to get a random verse
        function getRandomVerse() {
            return verses[Math.floor(Math.random() * verses.length)];
        }

        // Set the cat image to say a random verse on page load
        var randomVerse = getRandomVerse();
        document.getElementById('cat-image').src = "https://cataas.com/cat/says/" + encodeURIComponent(randomVerse);
        document.getElementById('cat-image').alt = "Cute Cat Saying: " + randomVerse;
    </script>
</body>
</html>
