# AddMoveToTopAndBottomButtons

Everyone will be able to move the rendering in the Device Editor Form to either the top position or the bottom location with the aid of this repository.

Why did we add this feature?

It is frequently necessary to position a new rendering in the device editor at the top, but if there are already a significant number of renderings present and if content authors add a new rendering to a content item, it is by default positioned at the bottom. If the control needs to be positioned at the top, the Move Up button must be clicked each time.So it can be a little annoying to repeatedly hit the Move Up button.

We've implemented the "Move To Top" and "Move To Bottom" buttons to make this possible.

![MicrosoftTeams-image (3)](https://user-images.githubusercontent.com/11225440/230072455-94f5425a-d2fc-4305-95b1-d0d0f189697e.png)

Process of implementation:

1. To accomplish this, we must copy deviceeditor.xml to the root directory at the following location: \sitecore\shell\Override\DeviceEditor.xml.
2. Copy the AddMoveToTopAndBottomButtons.dll file from the bin folder to the main directory's bin folder.




 
