# orient-display-OD-454
KiCad symbol and footprint for Orient Display's OD-454.

## Instructions to add the files to your project

Extract the project's zip file to a temporary folder.

**In KiCad project manager:**
* Select File -> New -> Project, write the name of the project as 'test_proj', select Save.
* Click Footprint Editor.

**In Footprint Editor:**
* File -> New Library -> Type 'test_proj.pretty' -> in Select Library Table, select Project -> OK.
* File -> Import Footprint from KiCad File ... -> Select the file 'OD-454.kicad_mod'.
* File -> Save As -> select the library 'test_proj.pretty' -> click Save.
* Close Footprint Editor.

**In KiCad project manager:**
* Click Symbol Editor.
* File -> New Library -> Type 'test_proj.lib' -> Save -> in Add to Library Table, select Project -> OK.
* File -> Import Symbol ... -> in Select Symbol Library, select 'test_proj' -> OK -> select the file 'od-454.lib' -> Open.

**In Symbol Editor:**
* Edit -> Properties ... -> in Library Symbol Properties, in tab General, in row footprint, click on the text 'footprintOD_454:OD-454' and click on the icon that shows up on the right of the text box.
* If 'Footprint library not found' shows up, click OK.

**In Footprint Library Browser:**
* Scroll down to test_proj, click on 'test_proj', on the right column, double click on 'OD-454', the browser will close.
	The updated text in the box should be 'test_proj:OD-454'.
* Back in Library Symbol Properties, click OK.
* Back in Symbol Editor, File -> Save, close Symbol Editor.

## To use the part:

**In KiCad project manager:**
* Double click test_proj.sch.

**In Eeschema:**
* Place -> Symbol -> click on the page area, or simply press 'A'.
* In Choose Symbol, scroll down, expand 'test_proj', and select 'OD-454', click on the page area to place the part.
