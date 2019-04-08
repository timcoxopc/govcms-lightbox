
# Image Gallery with Lightbox for GovCMS

## Purpose
Add an image gallery with lightbox to GovCMS

## Uses
Lightbox 2 by Lokesh Dhakar
https://lokeshdhakar.com/projects/lightbox2/

## Intructions
Everything you need is inside the deploy folder
- Copy css/gallery.css into the css folder in your theme
- Copy the /template/govcms-gallery folder into the templates folder in your theme
- Place the files inside the config directory in config/default and run: 'docker-compose exec -T test drush cim --partial'
- Run update.php / 'docker-compose exec -T test drush updatedb'

Use the gallery content type to create galleries.
