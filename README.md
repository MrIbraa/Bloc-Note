<!DOCTYPE html>
<html lang="fr">
    <BODY background=img7.jpg></BODY>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Application de Notes</title>
  <link rel="stylesheet" href="css.css">
</head>
<body>
  <div class="container">
    <center> <h1>Application de Notes</h1> </center>
    
    <center> <div class="input-area">
      <input type="text" id="note-input" placeholder="Entrez votre note ici...">
      <button id="save-btn">Enrengistrer</button>
    </div> </center>

    <div id="error-message" class="error-message"></div>
    
    <ul id="notes-list">
      <!-- Les notes seront affichées ici -->
    </ul>
  </div>

  <script src="java.js"></script>

</html>
