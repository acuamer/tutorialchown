<!DOCTYPE html>
<html lang="es">
   <title>Reproducción de tutorial-chown.cast con asciinema (v3)</title>
   <meta charset="utf-8">
   <link rel="stylesheet" type="text/css" href="https://unpkg.com/asciinema-player@latest/dist/bundle/asciinema-player.css" />
   <script>
      window.onload = function() {
         const player = AsciinemaPlayer.create('tutorial-chown.cast', document.getElementById("video"), {
            terminalfontSize: 'medium',
            fit: false,
            // speed: 1,
            // otros parámetros opcionales...
         });
         const audio = document.querySelector("audio");

         player.addEventListener("play", e => audio.play());
         player.addEventListener("pause", e => audio.pause());

         // Sincroniza audio y vídeo al cambiar de posición el vídeo.
         const bar = player.el.querySelector(".ap-progressbar");
         bar.addEventListener("click", e => audio.currentTime = player.getCurrentTime());
      }
   </script>

   <div id="video"><tutorial-chown.cast></div>
   <audio preload="auto"><source src="audiotutorial.webm" type="audio/webm"></audio>
   <script src="https://unpkg.com/asciinema-player@latest/dist/bundle/asciinema-player.js"></script>
