# orient-display-OD-454
KiCad symbol and footprint for Orient Display's OD-454.

Instructions to add the files to your project:
Extract the project's zip file to a temporary folder.
In KiCad project manager:
	1 Select File -> New -> Project, write the name of the project, select Save.
	2 Click Footprint Editor
In Footprint Editor:
	1 File -> New Library -> Type 'test_proj.pretty' -> in Select Library Table, select Project -> OK.
	2 File -> Import Footprint from KiCad File ... -> Select the file 'OD-454.kicad_mod'.
	3 File -> Save As -> select the library 'test_proj.pretty' -> click Save.
	4 Close Footprint Editor
In KiCad project manager:
	1 Click Symbol Editor
	2 File -> New Library -> Type 'test_proj.lib' -> Save -> in Add to Library Table, select Project -> OK.
	3 File -> Import Symbol ... -> in Select Symbol Library, select 'test_proj' -> OK -> select the file 'od-454.lib' -> Open.
In Symbol Editor:
	1 Edit -> Properties ... -> in Library Symbol Properties, in tab General, in row footprint, click on the text 'footprintOD_454:OD-454' and click on the icon that shows up on the right of the text box.
	2 If 'Footprint library not found' shows up, click OK.
In Footprint Library Browser:
	1 Scroll down to test_proj, click on 'test_proj', on the right column, double click on 'OD-454', the browser will close.
	The updated text in the box should be 'test_proj:OD-454'.
	2 Back in Library Symbol Properties, click OK.
	3 Back in Symbol Editor, File -> Save, close Symbol Editor.
To use the part:
In KiCad project manager:
	1 Double click test_proj.sch.
In Eeschema:
	1 Place -> Symbol -> click on the page area, or simply press 'A'.
	In Choose Symbol, scroll down, expand 'test_proj', and select 'OD-454', click on the page area to place the part.
