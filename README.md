# jQuery.lrc
jQuery Music Lyrics Plugin

## How to use?

    $("#music").loadLrc('.lyric',lrcUrl);
    
Where '#music' is an audio element and '.lyric' are elements for showing lyric lines.

    <audio controls="" name="media" id="music"><source id="music_src"></audio>
    <p class="lyric firstline"></p> <!-- Line 1 -->
    <p class="lyric otherlines"></p> <!-- Line 2 -->
    <p class="lyric otherlines"></p> <!-- Line 3 -->
    <p class="lyric otherlines"></p> <!-- Line 4 -->
    <p class="lyric otherlines"></p> <!-- Line 5 -->
    <script>
    $("#music").loadLrc('.lyric',lrcUrl);
    </script>

This will load the lyric file from lrcUrl and show lyrics in 5 p elements.
