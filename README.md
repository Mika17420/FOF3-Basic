# FOF3 Basic
A hello world type example for Akeeba FOF3  as a walkthrough for building a Joomla! component from the ground up.

**Note:** This step in the tutorial assumes you have FOF3 installed. If not, you can get an FOF3 install package from http://Akeebabackup.com

**Note2:** This step in the tutorial also assumes you have set up your component on a development site (local recommended). That means your Joomla development site needs your component installed with the database tables. You could also set up your tables, copy the files to the site, and add a record to the #__extensions table so you could browse directly to the component via [yoursite url or local url]/administrator/index.php?option=com_[your component's name i.e. fof3basic]... (but an install is easier since you'll have a menu item to work with)

## Step 2 - Browse your views and remove the scaffolding
In step 1 we set up everything to use FOF3's Quick prototyping Scaffolding features to build the views, and language files for us. All that we need to do with the files and database in place is browse to our component and look at each of the list views and item views. That's it, we have the prototype for our backend administrative interface via the Scaffolding feature. All we need to do now is copy the newly created files to our source control and turn off the Scaffolding development tool.

**Warning:** Remember if you ever turn on the Scaffolding development tool again, it will replace all of your view files and language .ini files and any customizations will be lost. The Scaffolding development tool should only be used for one time inital quick prototyping.

### For details see the following FOF3 documentation links
- [Getting started with an FOF component](https://github.com/akeeba/fof/wiki/Getting-started-with-a-FOF-component)
- [The fof XML configuration file](https://github.com/akeeba/fof/wiki/The-XML-configuration-file)
- [Table Structure Magic Fields](https://github.com/akeeba/fof/wiki/The-DataModel#magic-fields)
- [Quick prototyping with the FOF3 Scaffolding feature](https://github.com/akeeba/fof/wiki/Scaffolding)

### FOF3 Video Guides
- [Look, mum, no code! at J and Beyond 2015](https://youtu.be/qwPzNNAM5RA) Presented by Nicholas Dionysopoulos
  - [Github repository for code related to video tutorial](https://github.com/akeeba/jab15)

### Quick Links to Next/Previous Steps
- [Previous Step](https://github.com/photodude/FOF3-Basic/tree/step-1-basic-files)
- [Next Step](https://github.com/photodude/FOF3-Basic/tree/step-3-adding-the-site-side)

