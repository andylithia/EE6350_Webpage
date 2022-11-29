Steps to make a website using wpp -- 

   wpp is included in the template but can be found at https://sourceforge.net/projects/wpp/

1) Unzip the WebsiteTemplate.zip 
     unzip WebsiteTemplate.zip

   Rename the folder to your group name; XX is the number of your group
     mv WebsiteTemplate GroupXXWebsite	

   Go into the folder
     cd GroupXXWebsite
	
2) Testing wpp for the first time:

	i) Check the contents of the folder. It contains this README.txt and the basic files/folders needed for you to run wpp namely:
		a) kinget_course.css
		b) raw-files (folder) (contains index.raw file and other raw file examples and templates folder)
		c) images (folder)
                d) wpp-2.13 (folder) contains the perl script that will create the webpages from the raw and template files
	
	ii) make your webpages by running wpp as follows
                cd raw-files
                ../wpp-2.13/wpp *.raw
                  
	iii) This might give some warning, ignore it. It will create a webpage named index.html in the parent directory.
                cd ..
		ls 

	iv) You will see that index.html is created in GroupXXWebsite folder. You can now open it in browser.

3) Getting the header and footer ready:

	i)Go to the raw-files/templates/. Open head.tmpl in the text editor. Change the Project name and fill in the student names. (This is also the place where you will change the menu bar of your website as you add pages. See #4)

	ii) Go to the raw-files/templates/. Open tail.tmpl in the text editor. Change the copyright information as you are the authors of the website.
	
4) Creating new webpages using wpp: 

	i) Go to the templates folder (in raw-files). This contains the header and footer to be used in creating a webpage. Feel free to modify it as per your requirement. (Change the top navigation bar in the head.tmpl file.)

	ii) Look at the index.raw file and use it as an example for your other pages. A raw file needs to start with $Date$ at the top (refer index.raw) but simplest is to copy one of the examples files as a start for your new files.

	iii) Write the complete html content you intend to write in the body. No need to start and end the HTML body as it is taken care of in header and footer files.

	iv) In the terminal, in the folder raw-files, type the command:
		wpp *.raw

	v) It will create a *.html page for all your .raw files including header and footer by itself.

	vi) Make any changes in *.raw file and run the command again to create new .html file everytime.
	
5) Some suggestions:
	i) Do not share or upload any material on the website which you don't own or which can lead to copyright issues.
	ii) Include the actual die-micrograph in the submission, not the layout photo from cadence.
	iii) While adding references, please use IEEE format.
	iv) Use "References" instead of "Reference", "Conclusions" instead of "Conclusion", as there will be many references and conclusions that you will be talking about in the website. This is obvious, but these mistakes are very common.
	


Feel free to check more what can be done with wpp online. In case of any questions, contact: Sarthak Kalani, sk3779@columbia.edu
	
	

