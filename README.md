# FG-Core-RPG-Background-Changer
A Fantasy Grounds extension that allows you to easily change the whole background of the application by changing a filename in the code.
An example image that was downloaded as a free background is included as a sample, called 1.jpg.

# How to install?

1) Create a new folder in "Fantasy Grounds/Data/extensions" to hold the files.
2) Download all the files from the GitHub page for the project and place them inside.
3) When you start your campaign, select the 'FG Core RPG - Background Changer' extension.
Hint: Duplicate the folder and rename the extension name in "extension.xml" to something else for each of your campaigns. That way you can have different backgrounds for all your games.

# Why did I choose not to add the files into an .ext file?

Because the extension is made to be updated by yourself frequently as your campaign moves along. So it is easier to work with the files outside a compressed file.

# How to add a new background image?

Find an image you would like to use as a background, it should be of at least 2048 x 1080 pixels in size.
You can manually crop the image down to those pixels, or you can open up the included Photoshop file which is saved to those dimensions, and save your image from there.


# How to change the background image?

1) Open the "graphics/graphics_frames.xml" file.
2) Inside edit the name of the bitmmap file to whatever you want. Change the filename to the new image you want.
3) Reload the campaign, or type in "/reload" in the FG chat as the GM and press enter. This will reload your campaign with the new image.
Hint: I've found it convenient to name images from 1 and upwards as I add new backgrounds to reflect what the group is up to or where they're at.

	<!-- Desktop background -->
	<framedef name="desktop">
		<bitmap file="graphics/backgrounds/1.jpg" />
		<right rect="0,0,0,0" />		
		<middle rect="0,0,2048,1080" />
	</framedef>



# Changelog / Added / Modified:
Versioning: v(Major.Minor.Patch) https://en.wikipedia.org/wiki/Software_versioning

v1.0.0 (July 5th, 2019)
* All core functionality and files created and prepared for sharing.
- Created extension.xml
- Created graphphics_frames_xml
- Created Backgrounds.xml 
- Created example images.