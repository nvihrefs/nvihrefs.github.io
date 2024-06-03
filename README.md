<h1>Changelog</h1>

<h2>06/03/2024</h2>

-Fixed prefs menu bug where clicking bars to open -> clicking bars to close ->clicking menu area would reopen menu<br>
-Added specialty providers: Enloe, Glenn Medical Center, Adventist Health Feather River<br>

<h2>Planned Changes</h2>

<h3>Short-Term</h3>

-Add and update specialty provider info from old spreadsheet<br>
-Add imaging, labs, home health, pharmacies, dentistry, pediatrics<br>
-Update popup button scripts to match f and z (exp/col button changes, text scaling)<br>
-Use this.closest selectors for button scripts<br>
-Set popup scrollbar width to auto/none on expand/full/collapse<br>
-Fix notes width on normal/full/mini. align collapse button with notes. move button up 1px<br>
-Increase divtable header font size on full. <br>
-Ensure consistent font scaling with/between popup states<br>
-On minimize: collapse all expanded, scrolltop 0, remove active<br>
-Add .select when disabling copy click<br>
-Overflow scroll on fullscreen , hidden on non-full<br>
-Add if hotkeys == 1 to on F, on E, on Z pop scripts<br>
-Position minimized pop relative to existing previously minimized (var popcount)<br>
-Add tags to search by NPI and providers<br>
-Add tags to filter by location+specialty combinations (e.g. "chico, cardiology")<br>
--Add "report inaccuracy" option on right click (DOM element path on click?)<br>
-Make Preferences header less ugly<br>

<h3>Long-Term</h3>

-Migrate data to SQL<br>
-Add cookies/sessions to save user preferences<br>
-Add user logins<br>
-Use supabase for easy user auth backend? and to host db? or self-host?<br>
-Add user input. allow users to add notes in provider pop, add table rows (input form -> string interpolation)<br>
-Complete preferences menu<br>
-Add print option from full screen?<br> 
-Maybe revise full screen view as a whole<br>
-"Embed" NPI DB search (input from user -> load link containing input)<br>
-Clean up CSS<br>
-Minify<br>
