ALEX BOBBY SALBISTO - PORTFOLIO
================================

OPEN IT
  Double-click index.html. It opens in your browser (needs internet for the
  fonts and the 3D lanyard card).

CHANGE THE ABOUT PHOTO (normal picture + hover picture)
  1. Scroll to "About Me".
  2. Click the "Change photos" button on the bottom-right of the picture.
  3. For each slot, either:
       - tap one of your two photos (suit / selfie), or
       - press "Upload" and choose any picture from your computer.
     Slot 1 = the picture people see normally.
     Slot 2 = the picture that appears inside the circle when the mouse hovers.
  4. "Reset" puts that slot back to the default.

  Leave slot 2 empty (or press Reset) and the hover circle shows the
  automatic Spider-Man look made from picture 1.

  Note: pictures chosen in the panel are saved in YOUR browser only.

PUBLISH FOR EVERYONE (so visitors see your pictures)
  Save your two pictures in the same folder as index.html with exactly
  these names:
       about-photo.jpg   -> normal picture
       about-hover.jpg   -> hover picture
  Then open index.html with a plain text editor, find
       var SHOW_EDIT_BUTTON=true;
  and change it to
       var SHOW_EDIT_BUTTON=false;
  so visitors do not see the "Change photos" button. You can still open the
  panel any time by adding ?edit to the end of the page address.

  Tip: portrait pictures (taller than wide, 3:4) fit the frame best.

OTHER THINGS YOU CAN DO
  - Drag the 3D ID card at the top of the page.
  - In the music box, press "Add my songs" to build a worship playlist
    (songs stay on your device).
  - The contact form opens WhatsApp with your message ready to send.

FILES
  index.html        the whole portfolio (photos are embedded inside it)
  photos/           copies of the two original photos
  README.txt        this file
