<!DOCTYPE html>
<html lang="sv">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Min Hemsida</title>

  <!-- Font -->
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;700&display=swap" rel="stylesheet">

  <style>

	/* OBS, den här sidan är "kodad" med CGPT som faaan för jag kan inte 	koda for shit, gillar du inte html-gore så vet du vart dörren är */

    /* Tar bort allt standardskräp */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    /* Hela sidan */
    body {
      width: 100vw;
      height: 100vh;

      overflow: hidden;

      font-family: 'Montserrat', sans-serif;

      /* Bakgrundsbild från internet */
      background-image: url('https://live.staticflickr.com/65535/55252507585_53359864ce_h.jpg');

      background-size: cover;
      background-position: center;
      background-repeat: no-repeat;
    }

    /* Gemensam stil för all text */
    .text {
      position: absolute;

      color: white;

      opacity: 0.7;

      text-shadow: 0 0 10px black;
    }

    /* Text 1 */
    .title {
      top: 12%;
      left: 8%;

      font-size: 3rem;
      font-weight: 700;
    }

    /* Text 2 */
    .text2 {
      bottom: 10%;
      left: 10%;

      font-size: 1.5rem;
      font-weight: 300;
      max-width: 500px;
    }

    /* Text 3 */
    .text3 {
      bottom: 10%;
      right: 8%;

      font-size: 1.5rem;
      font-weight: 300;
    }

  </style>
</head>
<body>


  <!-- Stor rubrik -->
  <div class="text title">
    Stridsflygplan.se
  </div>

  <!-- Text -->
  <div class="text text2">
    JAS 39 Gripen - Är ett lättviktigt multiroll stridsflygplan designat för att verka ur svåråtkomliga miljöer med begränsade resurser för underhåll.
  </div>

  <!-- Text -->
  <a class="text text3" href="https://www.flickr.com/photos/24874528@N04/">
    Airwolfhound©
</a>

</body>
</html>
