# dynamic-folders

## problem

Day to day work always leads to some sort of unorganized, trashy folders.
Creating new folders and files on the fly, while in a rush will quickly let you end up with a Desktop looking similar to:

* New Folder (1)
    - Untitled Document (23).docx
    - Untitled Document (24).docx
    - Untitled Document (24) Copy 2.docx
    - Untitled Document (26).docx
    - Untitled Document (34) Important.docx
    - Untitled Document (45).docx
    - adfdsdgfsafsdfsd.txt

And today i had an idea when reading this xkcd:

![xkcd](http://imgs.xkcd.com/comics/documents.png)


## solution

Despite having the OS create 'Untitled Documents' or 'New Folders' one could have it create moreorless meaningful names,
following a mechanic i first saw at hashicorp's atlas (former vagrantcloud).

(VERB)-(NAME)-(RANNUM)

VERB   ... a simple verb taken from a dictionary
NAME   ... a name, also from a dictionary
RANDUM ... a 4-digit random number to add more entropy

Those files would fit their needs, being able to get edited and the user doesn't have to think of meaningful names.


Yet one could go a step further and have the os detect and determine which files belong together.
Based on this information and some learning algorithms, files could be grouped into folders.

*#GetsImplementedWhenIHaveTime*
