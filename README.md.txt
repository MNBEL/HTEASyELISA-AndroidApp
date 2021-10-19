At the top level is an "app" folder and a "Gradle Scripts" folder. This is in the android IDE, not sure how they are layed out in file manager.

I believe the gradle scripts take care of translating the files in the app folder to the android environment. like a pre-compiler of sort.

Gradle Scripts 
--> build.gradle in ELISA_App
	???
--> build.gradle in ELISA_App.app (i believe this .xxx structure denotes some folder / file hierachy)
	???
--> gradle-wrapper.properties
	???
--> proguard-rules.pro
	???
--> gradle.properties
	???
--> settings.gradle
	include statements and project name
--> local.properties
	???

app
--> manifests
	looks like some metadata about the phone resources 
	that are going to be used and what 'activities' will
	be present.
(activities seem to be somewhat synonomous with states of the screen that the app can be in, with control and graphics and such on each of these screens.

--> java
	--> com.micronanobio.elisapp
		contains a series of classes written in java. i'm not sure but these may correspond to activities... no it doesn't seem like the do... we'll see how they're used later on perhaps
	--> com.micronanobio.elisaapp (androidTest)
seems to be some build in testing. not sure if it is used or not
	--> com.micronanobio.elisapp (test)
same as above, seems to have something to do with tests...

--> java (generated)
I assume this is some code that is generated
	--> com.micronanobio.elisapp
contains a single file, BuildConfig, which contains a single class that i assume specifies something about the program is build
--> res
short for resources
	--> drawable
contains all sorts of files for generating graphics. mostly png's (transparency important no doubt) of graphics and such.
also contains some xml files where graphics can be plotted or can combine and format other resources. also a couple built in xmls perhaps used with android???

	--> layout
contains a series of xml files that visually lay out the different screens, the graphics, and the buttons associated with them.
(what exactly is an xml file and what all can it do / is it meant to do.
	--> mipmap
appears to contain some built in android resources
	--> values
appears to contain maybe some sort of global variables for things such as commonly used colors and such?
	--> themes
perhaps built in, denotes colors in an html like (what's this called) way of using things. like 'colorPrimary' and 'colorSecondary'
	--> xml
???
--> res (generated)
	???





