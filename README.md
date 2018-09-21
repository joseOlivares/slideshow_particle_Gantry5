# slideshow_particle_Gantry5
My updated version of Gantry 5 slide show particle

Hi my name is Jose Olivares, this is my updated version of the slideshow Gantry 5 particle (it is based on the inspiretheme free slideshow particle).


What's new?
 
-It uses the updated UIkit 3 framework

-Some new parameters added in order to a better customize of the slideshow.


Note: This release is not fully tested, I made it because I need it into a  projec.


#Installation in Joomla:

1-Copy the slideshowui3.html.twig and slideshowui3.yaml files to root/templates/TEMPLATE_DIR/custom/particles (if the particles folder does not exist, you have to create it manually)

2-Copy the _slideshowui3.scss file to root/templates/TEMPLATE_DIR/custom/scss (if the scss folder does not exists, you will need to create it manually)

3- Add the following code in your custom.scss file.

	@import "dependencies";
	@import "slideshowui3"; // Slideshow Particle

  If the custom.scss file does not exists, you will need to create it manually. Also, make sure your custom.scss file has the @import "dependencies"; code at the very top.


#Install Uikit3 inside Gantry5 Joomla Template

1-Copy the css and js folders to root/templates/TEMPLATE_DIR/custom/uikit (if the uikit folder does not exist, you have to create it manually)

2-Copy the uikit.html.twig and uikit.yaml files to root/templates/TEMPLATE_DIR/custom/particles (if the particles folder does not exist, you have to create it manually)

3-Add uikit for Gantry5 framework to your Gantry 5 Template (search for Setting Page tab)
