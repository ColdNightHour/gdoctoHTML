# gdoc to HTML
A simple add-on for google-docs that allows the user to make a selected google-doc table into an HTML table. 

##To ''Install''
Since it is not yet published (which I am working on) you must paste the code in a google doc script editor. 
Follow the below instructions.

1. Create a new google doc, and create a table.

2. Then in the tabs above select ``Tools->Script editor...``.

3. From here if you have not used this before you will be prompted with an option to make a blank project. 
Select this option.

4. In the file that is opened up copy and paste the .gs file within provided in this repo.

5. Once this is done, open a new HTML file from the file tab above and copy and paste the .HTM file within provided by this repo. NAME THIS FILE --> Sidebar.html 

6. Next save the project as whatever you please.

##To use
1. Return to your original document that has the table.

2. Navigate to the tab called ```Add-ons``` where you should see the name (which you chose) of the add-on.
Hover over it and select start.

3. Once this is done the add-on will appear as a side-bar, with a default column size of 2.

4. Select your table (that means highlight the whole thing as you would any text and press the translate button
in the add-on side-bar. The HTML should now appear in the text-area.

##Behavior
In order for the add-on to work the table must be populated uniformly. This means that if you have a 4x4 table, each row must contain at least one thing in a cell.
