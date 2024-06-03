<h2>Changelog</h2>

<h3>06/03/2024</h3>

-Live.

<h2>Planned Changes</h2>

<h3>Short-Term</h3>

-Add and update specialty provider info from old spreadsheet<br>
-Add imaging, labs, dentistry<br>
-Update popup button scripts to match f and z (exp/col button changes, text scaling)<br>
-Use this.closest selectors for button scripts<br>
-Set popup scrollbar width to auto/none on expand/full/collapse<br>
-Fix notes width on normal/full/mini. align collapse button with notes. move button up 1px<br>
-Fix prefs menu bug. Click bars to open -> click bars to close -> click menu area reopens menu
-Increase divtable header font size on full. <br>
-Ensure consistent font scaling with/between popup states<br>
-On minimize: collapse all expanded, scrolltop 0, remove active<br>
-Add .select when disabling copy click<br>
-Overflow scroll on fullscreen , hidden on non-full<br>
-Add if hotkeys == 1 to on F, on E, on Z pop scripts<br>
-Position minimized pop relative to existing previously minimized (var popcount)<br>
-Add tags to search by NPI and providers<br>
-Add tags to filter by location+specialty combinations (e.g. "chico, cardiology")
-Make Preferences header less ugly<br>
-Clean up CSS<br>

<h3>Long-Term</h3>

-Migrate data to SQL
-Add cookies/sessions to save user preferences<br>
-Add user logins
-Use supabase for easy user auth backend? and to host db? or self-host?<br>
-Add user input. allow users to add notes in provider pop, add table rows (input form -> string interpolation)<br>
-Complete preferences menu<br>
-Add "report inaccuracy" option<br>
-Add preference toggle for right click to copy<br>
-Add print from full screen<br>
-"Embed" NPI DB search (input from user -> load link containing input)<br>
-Minify<br>
