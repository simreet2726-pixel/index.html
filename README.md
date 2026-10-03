Happy Birthday, Sumit! 🎂
An interactive birthday website made with love by Simran, as a surprise for her best friend.
Live site: https://<your-username>.github.io/<repo-name>/
What's inside
3D gift box that spins and has balloons orbiting around it. Drag to rotate, tap to open.
3D photo cube with our photos on its faces. Drag to spin it.
Flip cards for photos, each with a message on the back.
"Why are you so special?" button that reveals one reason per tap.
Balloon pop game, with a birthday wish hidden in every balloon.
A runaway "No" button for the question "Will we stay best friends forever?"
Happy Birthday tune played in the browser.
Confetti and sparkles whenever you tap.
Tech
Plain HTML, CSS and JavaScript in a single file (index.html)
three.js (r128, loaded from cdnjs) for the 3D gift box
CSS 3D transforms for the photo cube and flip cards
Web Audio API for the music
Canvas for confetti
No build step, no dependencies to install.
Run it locally
Download or clone this repo.
Open index.html in any modern browser.
An internet connection is needed for the 3D gift box (three.js) and the fonts.
Deploy with GitHub Pages
Push index.html to a public repo.
Go to Settings → Pages.
Set Source to "Deploy from a branch", branch main, folder / (root), then Save.
After a minute or two, your link appears on the same page.
Customize
Open index.html and look for these parts:
Name: change const NAME="Sumit" near the start of the <script>.
Messages: edit the reasons and wishes lists, and the text inside the letter section.
Photos: the two photos are stored inside the IM list as base64 data. Replace them with your own images converted to base64, or change the <img> tags to point to image files in the repo.
Note
The repo and the site are public, so anyone with the link can see the photos. Only share the link with people you trust.
Made with 💛 for Sumit.
