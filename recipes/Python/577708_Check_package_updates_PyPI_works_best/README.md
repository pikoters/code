## Check for package updates on PyPI (works best in pip+virtualenv) 
Originally published: 2011-05-19 17:54:42 
Last updated: 2011-05-19 17:54:43 
Author: Artur Siekielski 
 
Pip has an option to upgrade a package (_pip install -U_), however it always downloads sources even if there is already a newest version installed. If you want to check updates for all installed packages then some scripting is required.