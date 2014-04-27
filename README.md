# Test DocPad site deployed to an Azure WebSite

This is a DocPad demo that I have deployed to an Azure WebSite.

Azure is pulling this repository from GitHub. It then runs DocPad to generate the static HTML site then copies the new static files to the deployment folder where they can be served publicly. 

This is all done automatically and means that it is not necessary to pre-compile the static HTML files on your local system and publish those files.

_Take a look at the .gitignore file you will see that the no files from the local /out folder are being pushed to this repository._

This process was achieved from the instructions at [DocPad's Deployment Site](http://docpad.org/docs/deploy#for-deployment-to-windows-azure) and from [Nathan Tottens blog](http://ntotten.com/2013/01/11/static-site-generation-with-docpad-on-windows-azure-web-sites/).