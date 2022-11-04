CMPUT404-assignment-ajax
==============================

CMPUT404-assignment-ajax

See requirements.org (plain-text) for a description of the project.

Make a shared state AJAX drawing program

Contributors / Licensing
========================
* rmo1 - helped me get a sense of the server.py udpdate, helped get a sense for how update() should work 
  and showed me how to send a xml response.
* ianta - helped me figure out how to make a call to sendXMLRequest (inside addEntity) and gave me and 
  idea on how to update the frontend canvas (inside update).
* truonggi - Helped me get started on sendXMLRequest (explained what i should be returning inside onReadyStateChange).
* og - Helped me fix update() so that there are no latency issues
* landberg -  helped me make sure I didn't miss any cases involving the server.py (edgecases)
* archit2 - Helped me by showing me how to fill circle entirely and showed me how to change the colour of the circle as
  I click it (showed me that we need to make a global variable above the mouse click event and we need to insert the color
  change inside the Update function using another global variable).

External Code:
* Code to generate gradient inside circle came from here:
  * https://stackoverflow.com/questions/16494262/how-to-draw-a-circle-with-centered-fadeing-out-gradients-with-html5-canvas
Generally everything is LICENSE'D under the Apache 2 license by Abram Hindle.


