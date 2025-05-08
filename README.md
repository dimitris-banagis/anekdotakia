# anekdotakia
<!DOCTYPE html>
<html lang="el">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Anekdotakia</title>
  <style>
    body { font-family: sans-serif; text-align: center; padding: 50px; background: #fffce6; }
    .joke-box { background: #fff; padding: 30px; border-radius: 10px; box-shadow: 0 0 15px rgba(0,0,0,0.1); max-width: 600px; margin: auto; }
    .joke { font-size: 24px; margin-bottom: 20px; color: #333; }
    .refresh { font-size: 14px; color: #999; }
  </style>
</head>
<body>
  <div class="joke-box">
    <div class="joke" id="joke">Φόρτωση αστείου...</div>
    <div class="refresh">Κάνε ανανέωση για άλλο ανέκδοτο! 🔁</div>
  </div>

  <script>
    const jokes = [
      "Πώς λέγεται το κουνούπι στο Facebook; – Τσιμπητής!",
      "Γιατί οι υπολογιστές δεν λένε ψέματα; – Γιατί έχουν byte συνείδησης!",
      "Τι είπε το μηδέν στο οχτώ; – Ωραία ζώνη!",
      "Πώς λέγεται ο σκύλος που κάνει μαθήματα; – Καθηγητής!",
      "Ποιο είναι το αγαπημένο φρούτο του ηλεκτρολόγου; – Το βύσσινο!"
    ];

    const randomIndex = Math.floor(Math.random() * jokes.length);
    document.getElementById("joke").textContent = jokes[randomIndex];
  </script>
</body>
</html>
