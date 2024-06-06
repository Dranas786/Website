Actual Notes:
Remove Chamges to do
Run npm install -g @sanity/cli to use sanity command line interface commands.
Client.js file in frontend/src manages the connection between sanity and react using API tokens.
The .env file in frontend acts as a safeguard to protect the project_id and token

Changes to do:

1. In assests logo image (and as the name stays the same don't need to change it in constants/images.js export and import)
2. Change profile too
3. Line 61 ib Header.jsx has flutter and redux as images, might switch it with things I have skills in
   If addedor removed skills also remove or add the thing below in header.scss
   div:nth-child(1) {
   width: 100px;
   height: 100px;
   }
4. Change the abouts object array in About.jsx (can also change the logo in the file) (and also change the image urls in this array of about objects) (actually now the about objects are linked to sanity so change it from there)
5. Change creative portfolio array (prolly gonna be objects from sanity) (static for now) (actually both change static array line 31(tag array) and Works section in sanity)
6. Also update skills in sanity
