Activity Creation Templates For Android Studio

Android Studio uses the ConstraintLayout as the default layout for newly created Activities. A developer must manually change or create
the Activity's associated layout file if a different layout is desired. This is not difficult, but it can become annoying. I've created
two new EmptyActivity templates to use when creating a new Activity, one for LinearLayout and one for RelativeLayout.

One folder and two files need to be installed for each EmptyActivity template. Installation instructions follow. 
               
Installation Steps
 1) Navigate to the activities folder for your Android Studio installation
	Mine is here - C:\Program Files\Android\Android Studio\plugins\android\lib\templates\activities

 2) Copy and paste the EmptyActivityLinearLayout and EmptyActivityRelativeLayout folders into this activities folder

 3) Navigate to the activities/common folder

 4) Copy and paste the recipe_simple_linear.xml.ftl and recipe_simple_relative.xml.ftl files into this folder

 5) Navigate to the activities/common/root/res/layout folder

 6) Copy and paste the simple_linear.xml.ftl and simple_relative.xml.ftl files into this folder

 7) Restart Android Studio - You will now have the option to create an EmptyActivity with your choice of layout when
    creating a new project or Activity.

***Note that these files will be removed when Android Studio is updated as they are deemed to be unexpected files. They will need to be 
reinstalled after such an update.