<!DOCTYPE html>
<html>
<head>
    <title>Demande à Fleur</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(to right, #ff758c 0%, #ff7eb3 100%);
            color: white;
            text-align: center;
            padding-top: 50px;
        }
        .valentine-box {
            background-color: rgba(255, 255, 255, 0.8);
            border-radius: 15px;
            padding: 20px;
            margin: auto;
            width: 50%;
            box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
        }
        button {
            display: inline-block;
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
            text-align: center;
            margin: 10px;
            text-decoration: none;
            color: #ff758c;
            background-color: white;
            border: 2px solid #ff758c;
            border-radius: 5px;
            transition: all 0.3s ease;
        }
        button:hover {
            background-color: #ff758c;
            color: white;
            border-color: white;
        }
        #video, #responseMessage {
            display: none;
            margin-top: 20px;
            color: white;
        }
    </style>
</head>
<body>
    <div class="valentine-box">
        <h1>Salut Fleur!</h1>
        <p>Accepterais-tu d'être ma Valentine?</p>
        <button onclick="showVideoAndMessage()">Oui</button>
        <button onclick="alert('Peut-être une autre fois alors...')">Non</button>
    </div>
    <div id="responseMessage">
        <p>Tu avais intérêt, ma pétasse :)</p>
    </div>
    <div id="video">
        <iframe width="560" height="315" src="https://www.youtube.com/embed/x0eGFZ6mcmg" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
    </div>

    <script>
        function showVideoAndMessage() {
            document.getElementById("video").style.display = "block";
            document.getElementById("responseMessage").style.display = "block";
        }
    </script>
</body>
</html>

