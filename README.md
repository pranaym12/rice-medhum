# rice-medhum: Tips for the webmaster
<a href="http://medhumclub.rice.edu">Website for Rice Medical Humanities Club</a>

<h2>Updating MedHum Website:</h2>
On Mac, open up Finder and hit Cmd+K to open a box that says "Open a server". Type in the following url and hit enter:
http://storage.rice.edu/Student Activities/Public/www/medicalhumanities.rice.edu 


On Windows, click the start button and in the text box type this URL and hit enter/return: 
\\file-rnas.rice.edu\static-web\medhumclub\www

If that URL doesn't work, try 
\\storage.rice.edu\Student Activities\Public\www\medicalhumanities.rice.edu 

You may or may not need to remove the double slashes at the beginning? Also I can't confirm if this works since I'm on Mac.
You may also need to put http:// (or something like that) if you keep getting an error where it says "URLs with the type ':' are not supported".


Hit connect, and login in with your Rice NetID / Password (the same login you use for Canvas). 
Then you can just replace files with the updated ones. (Or, if you're feeling spicy, you can update the HTML right there - but make sure to update the changes in the Github!) 

<h2>Setting up a VPN</h2>
This will let you connect to Rice wifi remotely. Find the section that says VPN on <a href="https://kb.rice.edu/page.php?id=65468">this webpage</a>, click the link, and follow the instructions for your OS. Here are the instructions for <a href="https://kb.rice.edu/internal/page.php?id=83592">Mac</a>.

<h2>Updating officer photos</h2>
Every line for the officer photos has something that says 'alt = "Adam Smith"' where there's somebody's name in place of Adam Smith. You can delete this part. I just let it be.

Although in order to make the photos circle-y, you have to ensure that each of the photos has approximately the same height as width. You may need to crop the photos. If a photo is too tall, it'll render as a skinny oval on the website; and if photo is too wide, it'll render as fat oval.

<h2> Guide to Github</h2>
<h3>Downloading the MedHums Github repository and getting contributor access</h3>
This is the MedHums Github repository - this is the place in the cloud where the code is stored, and every change made to the code is tracked. First, to make changes, you need to be a contributor to the repository, so that any changes you make will be tracked and uploaded to Github. Make sure you have a Github account, and then ask whoever is the admin/owner of the repository (currently Pranay Mittal) to add you as a contributor.

<h3>Setting up Github</h3>
Set up Github on your computer. (If you've never used Github before, the desktop client makes it easy.) Now, we'll download the code to your computer: on the Github repository page, see the green button with a downward-pointing arrow that says "Code"? Click on that and click the clipboard which copies a URL to your copy/paste. Then clone the repository (if you know what this means, skip this sentence): on  Github Desktop, click around to find a button that says "Add" => "Clone repository", and paste your link there, and hit enter. This will download the code to your computer, and allow you to upload any changes you make to the Github client.

<h3>Setting up a branch and making changes</h3>
Wooo you have code on your computer now! If you want to make changes, use Github to create a new branch Now, you can make changes. If you want to make any changes, make a new branch. (Think of a new branch as like a "working area" where you can test out changes to the code, and when you're happy with the changes, you merge them with master, which is the final/polished version of the code.) On Github desktop, to make a new branch, hit "Current branch", "New branch", and then make a branch. 


Then you can make changes to the code. When you make a change, you commit it: on Github desktop, write a summary in the bottom left, and hit "commit". 


Once you're happy with all your changes, you "publish your branch" (upload the existence of your branch to Github), and then "push to origin" (upload the actual changes made to your branch to Github (origin = Github)). 

<h3>Updating code on Master</h3>
When you're done making all the changes you want to make, make a "pull request". (What you're doing is requesting to "pull" your code changes into the master branch.) 


Click "create pull request", which takes you to the github website, hit "compare & pull request"

Then make the Pull Request.

If everything looks good, hit "merge", confirm the merge, and your changes have been updated to the master branch on Github! There'll be a little popup to delete the old branch, and unless you have a reason to keep the old branch, you can go ahead and do that.
