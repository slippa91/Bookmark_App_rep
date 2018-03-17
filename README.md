# Bookmark Extension

<https://chrome-bookmark-app.herokuapp.com/> \
Version 1.0 \
Deployment Date: March 20, 2018  \
Contributors: Efosa Ogiesoba, Faizan Salman & Susan Lippa

\
#Purpose

Bookmark Extension is an application that makes a database copy of your Google Chrome bookmarks and then renders them in a personal library.  From the library you can search for a Bookmark by its title, access a bookmark's web page,  create folders, assign the folders to the bookmarks and sort them accordingly.  


# Getting Started

In order to use the Bookmark Extension, you will need to install our Chrome extension.

Go to the Chrome Extension Web Store using the following link and then click 'Add to Chrome' in the upper

https://chrome.google.com/webstore/detail/bookmarksextension/bmcedhkdcpghcododeoabjphojpigcoe?hl=en-US&gl=US 



![Chrome_Extension Store](public/images/ChromeExtensionLoadPage.png)


A window will put up confirming the Extension Load. Click 'Add Extension".


![Bookmark Extension Icon](public/images/ChromeExtenstionAdd.png)

Another box will appear when the Extension has loaded. Click on the X in the upper right hand corner of the box to close the popup. You will notice that a new Extension icon will appear on your Chrome page. You are ready to being using the Bookmark Extension. 

![Bookmark Extension Icon](public/images/ExtensionLoadConfirm.png)



# Instructions

\
#Login

\
To start, click the Bookmark Extension icon located in the upper right-hand corner of your Chrome Window.

![Bookmark Extension Icon](public/images/ChromeExtIcon.png)

\
Once you have loaded and clicked the Bookmark Extension icon, the following window will appear:


![Bookmark Extension Open Window](public/images/Chrome_ExtensionInitial.png)

\
You will need to:

1) Input your Gmail address - This register's your email to our database. It becomes your login going forward. Your email will be saved so you should not have to re-enter it into this page. 

2) Click the 'Register/Login' button - This downloads your bookmarks into our database.

3) Click the 'To Bookmark Home' button - This will take you to your Bookmark Extension library.


![Bookmark Extension Window](public/images/Chrome_ExtensionRegister.png)

\
When the 'To Bookmark Home' button is clicked, the following modal will appear. We ask you to input the same email that you used to register on the Chrome extension page. This allows us to link the bookmarks that were downloaded to the display you are about to see.


![Modal Login Window](public/images/ModalLogin.png)

\
\
#Bookmarks

\
From the modal login, you will be taken to the main Bookmark Extension homepage. Here you will see a rendering of all your bookmarks. Each bookmark is comprised of 4 sections: the title, the link the web page, the folder section and the delete section. 


![Bookmark Page](public/images/BookmarkPageFull.png)


\
The title section is searchable using the input bar located at the top of the home page.


![Bookmark Page Search Bar](public/images/SearchBar.png)


\
To create a bookmark, make sure your active tab in Chrome is the one you want to bookmark then click on the original Bookmark-Extension icon. 

When the extension window opens you will notice that the application recognizes you as logged in. 

To add a new Bookmark, first add a title for the bookmark in the form area. Then press "Click to Bookmark Current Page". This will save the bookmark to the database. To access your new bookmark, click the 'To Bookmarks Home' button. The modal will reappear and ask to reconfirm your login. Your new bookmark will be rendered at the bottom of the bookmark list. 

![Creating New Bookmark](public/images/NewBookmark.png)

\
\
#Folders

\
 To access the 'Folder' section of the Bookmark Extension, click on the 'Folder Bar' button located in the upper left hand corner of the homepage. You can click on the 'Folder Bar' button again to hide the folder section. 


![Folder Bar](public/images/FolderBar.png)

\
At this time, we are not able to import your existing Chrome folders. All bookmarks are created with the 'No Folder Assigned' tag. To create a folder, type the folder name in the 'Add Folder Name' bar and click submit. Your new folder will be added to the list. 


![ New Folder](public/images/CreateFolder.png)

\
Once folder have been created, you can assign them to bookmarks by dragging the line of the folder over into the folder section on the bookmark. 



![Folder Assign](public/images/FolderAssign.png)

\
To search by a particular folder, just click on the name and all the folders with that designation will appear in the window.

![Folder Search](public/images/FolderSearch.png)

\
To delete a folder, click on the "-" sign to the left of the folder name. You will get an alert that will inform you that deleting a folder will also delete all of its associated bookmarks. If you do not wish to delete the bookmarks, you will have to reassign them to a different folder. 

![Folder Delete](public/images/FolderDelete.png)

\
That is all there is too it. Enjoy using our Bookmark Extension.


# Built Using

Chrome Extension:  <https://developer.chrome.com/extensions/getstarted> \
Bootstrap 4:  <https://getbootstrap.com/> \
StartBootstrap Simple Sidebar: <https://startbootstrap.com/template-overviews/simple-sidebar/>


# Original Contributors

Efosa Ogiesoba: <https://github.com/eogiesoba> \
Faizan Salman: <https://github.com/Faizy711> \
Susan Lippa: <https://github.com/slippa91>


# Original Idea

The idea originally began with Efosa Ogiesoba. He was interested in a more visual and dynamic way to work with his Chrome bookmarks. This corresponded well with a project that required database integration, API calls and a polished UI. Although working with a Chrome Extension has presented some developmental challenges, it has ultimately been a rewarding experience. 

![Original Efosa Drawing](public/images/OriginalDrawing.jpg)


# IceBox

There are several ideas pending for possible future development.

1) Integrating the login between the Extension and the home page.
2) Adding a 'Notes' feature to each bookmark.
3) Allowing folders and bookmarks to be dynamically renamed.
4) Allowing folders to be deleted either with or without their corresponding bookmarks.
4) Allowing a bookmark to exist in multiple folders.
2) Evolving the codebase to React.js to allow for individual rendering of the bookmark and folder elements.



# Ideas for Improvement:

Have additional ideas for improving this site? Please first discuss the change you wish to make via email with the owners of this repository. Email addresses can be found on the contributor's gitHub pages (links above).









