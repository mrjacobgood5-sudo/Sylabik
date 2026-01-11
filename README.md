<!DOCTYPE html>
<html lang="pl">
<head>
<meta charset="UTF-8">
<title>Orientacja Sylabiczna</title>
<style>
  body {
    margin: 0;
    padding: 40px;
    font-family: serif;
    color: #eee;
    background-image: url("twoje_zdjecie_tla.jpg"); /* TU PODMIENIASZ TŁO */
    background-size: cover;
    background-position: center;
  }
  .box {
    background: rgba(0,0,0,0.6);
    padding: 30px;
    max-width: 700px;
  }
  h2 { margin-top: 30px; }
  table {
    width: 100%;
    border-collapse: collapse;
  }
  td, th {
    border-bottom: 1px solid #555;
    padding: 6px;
  }
  .poem {
    font-style: italic;
    margin-top: 20px;
  }
</style>
</head>
<body>

<div class="box">
  <h1>Zdanie (wpis użytkownika)</h1>
  <input type="text" value="kamień jest okrągły" style="width:100%; font-size:16px;" disabled>

  <h2>Krok 1 — sylaby</h2>
  <p>ka / mień / jest / o / krą / gły</p>

  <h2>Krok 2 — sylaba → słowo + sens</h2>
  <table>
    <tr><th>sylaba</th><th>słowo</th><th>sens</th></tr>
    <tr><td>ka</td><td>kamień</td><td>coś stałego, obecnego</td></tr>
    <tr><td>mień</td><td>mienie</td><td>to, co się posiada</td></tr>
    <tr><td>jest</td><td>jest</td><td>istnienie</td></tr>
    <tr><td>o</td><td>okrąg</td><td>bez początku</td></tr>
    <tr><td>krą</td><td>krąg</td><td>powrót</td></tr>
    <tr><td>gły</td><td>okrągły</td><td>domknięcie</td></tr>
  </table>

  <h2>Krok 3A — zdanie z samych słów</h2>
  <p>Kamień mienia jest okręgiem kręgu okrągłego.</p>

  <h2>Krok 3B — zdanie z sensów</h2>
  <p>To, co jest obecne, istnieje jako coś posiadanego i naturalnie domkniętego.</p>

  <h2>Krok 4 — wiersz</h2>
  <div class="poem">
    Nie trzeba rozumieć.<br>
    Wystarczy być.<br>
    To, co trwa,<br>
    wraca spokojnie.
  </div>
</div>

</body>
</html>
