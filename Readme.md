# Steps to Run the project (on local host) #
    a) Download the project folder from the github page & Extract the file on local host
    b) Open the extracted folder and run the “index.html”
    
# Steps to deploy (on Heroku) #
    a)	Create a github repo with the project files. Heroku needs a backend language code – So include a “index.php” with following code in it – 
                                        <?php header( 'Location: /index.html' ) ;  ?>
    b)	Now go on Heroku and make a new account if you don’t have it.
    c)	Log into your account and make a new app. 
    d)	Once the app is made, select connect to github in the popup opend give access to Heroku to check on repositories in the git profile.
    e)	Then give your github repo name and click on connect.
    f)	It will automatically connect and deploy the code. Once deployed, open the app with the url given In the app dashboard.
    
# Project features #
    a)	Allows user to upload a file and displays the contents of the file in the app.
    b)	Carry’s out a spell check on every word of the file (with the help of textgears api)
    c)	For every word where there's a spelling mistake, highlights the word in red colour.
    d)	On right click of a highlighted word, provide a custom menu which has correct spelling suggestions in it. 
    e)	On click of any correctly spelled word, the wrongly spelled word is replaced by its correct spelling chosen by the user.
    
# Screen shots # 
<img width="957" alt="SC 1" src="https://user-images.githubusercontent.com/51018572/101542249-84d92d80-39c8-11eb-96c0-e7a5b2143dfb.png">
<img width="960" alt="sc 2" src="https://user-images.githubusercontent.com/51018572/101542256-86a2f100-39c8-11eb-9399-18f17aec11ea.png">
<img width="960" alt="sc 3" src="https://user-images.githubusercontent.com/51018572/101542257-873b8780-39c8-11eb-8a50-4a1007a766ad.png">
<img width="958" alt="sc 4" src="https://user-images.githubusercontent.com/51018572/101542259-87d41e00-39c8-11eb-9fab-427e1d0cc1a0.png">
