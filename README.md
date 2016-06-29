# Max-Autosave
Autosave feature for MaxMSP (pre Max7)

I got tired of Max crashing and not having saved in a while so I wrote this template patch to auto save every 5 minutes.

For the template to appear in File, you need to put the maxpat in the patches > templates folder. 

To use the template select File > New From Template > autosaveTemplate 

When the patch loads a dialog box will prompt you to select a save location and name for the file. 

Then every 5 minutes the patch will be saved!  If you want to change how often the patch is saved just change the metro time. 

Note: I've tried encapsulation but "write -- thispatcher" will only save the work that has been done in the patch window that thispatcher is in. 
(a little obvious from the name but I still wanted to try :)

I wonder if anyone else has a more elegant solution? 
