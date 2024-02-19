# Welcome!
**You Have Access to Work on ReZ!**
This is  Going to Become Open Source (For Modding) After Release!

## How to Edit:
Upon Opening, Open The Desired Scene, Then Go To the Events and Open the External Events, I use External Events to Edit Code Across Scenes!
### Editor Editing:
When Making a New Editor Object, Make the Object, Add its Code in the External Events: `Main` And Add the Object to the Object Group: `Objects` Finally, Duplicate the `objectlistitem`
And Edit its Instance Variables, Lets go Over Them, `Position`: THe Order of the List Item, `IsFolder`: If its a Folder, Make Sure its in the `Root` Folder, `Title`: the Display Text for the List Item,
`Object`: If `IsFolder` is False it sets the Selected Object to this Object (Make Sure you Spell it Right) and if `IsFolder` is True it sets the current folder to whatever its set to, and Finally, 
`Folder`: What folder the List Item is in, set it to "root" to be in the Default Folder, In Root, Only Put Folders, not Objects, Objects go In Folders.
