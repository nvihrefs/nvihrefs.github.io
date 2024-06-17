<h1>Planned Changes and Changelog</h1>

<h2>Planned Changes</h2>

<h3>Short-Term</h3>
<ul>
<li>Add and update all specialty provider info from old spreadsheet</li>
<li>Add imaging, labs, home health, pharmacies, dentistry, pediatrics</li>
<li>Update popup button scripts to match f and z (exp/col button changes, text scaling)</li>
<li>Use this.closest selectors for button scripts</li>
<li>Set popup scrollbar width to auto/none on expand/full/collapse</li>
<li>Overflow scroll on fullscreen , hidden on non-full</li>
<li>Fix notes width on normal/full/mini. align collapse button with notes. move button up 1px</li>
<li>Make copied text popup circle x smaller</li>
<li>Increase divtable header font size on full.</li>
<li>Ensure consistent font scaling with/between popup states</li>
<li>On minimize: collapse all expanded, scrolltop 0, remove active</li>
<li>Add .select when disabling copy click</li>
<li>Add if hotkeys == 1 to on F, on E, on Z pop scripts</li>
<li>Add tags to search by NPI and providers</li>
</ul>

<h3>Long-Term</h3>
<ul>
<li>Move data to SQL</li>
<li>Add cookies/sessions to save user preferences</li>
<li>Add user logins</li>
<li>Use supabase for easy user auth backend? and to host db? or self-host?</li>
<li>Add user input. allow users to add notes in provider pop, add table rows (input form -> string interpolation)</li>
<li>Complete preferences menu</li>
<li>Add print option from full screen?</li>
<li>Maybe revise full screen view as a whole</li>
<li>Position minimized pop relative to existing previously minimized (var popcount)</li>
<li>Add "report inaccuracy" option on right click? (DOM element path on click?)</li>
<li>"Embed" NPI DB search (input from user -> load link containing input)</li>
<li>Recently Added Entries pane</li>
<li>Clean up CSS</li>
</ul>

<h2>Changelog</h2>

<h3>06/17/2024</h3>
New features:
<ul>
<li>Added search tags to filter specialty results by location and primary insurance using syntax "specialty city insurance", or "specialty county insurance", or "specialty insurance".</li>
</ul>

Corrections:
<ul>
<li>Reeve Woods note</li>
</ul>

<h3>06/10/2024</h3>
Bug fixes:
<ul>
<li>Popup header text will no longer overflow into buttons (Added container for header text)</li>
<li>Show/hide all button and hotkeys no longer hide/show Notes field (Added notes0 class)</li>
<li>Show/hide all button toggle fixed</li>
<li>Popups are now slightly wider</li>
<li>Closing a popup now fully restores it to its original size, position, and unexpanded state.
</ul>
New entries:
<ul>
<li>Medical providers:</li>
<ul>
<li>Advanced Pain Diagnostic and Solutions</li>
<li>Adventist Health Feather River and Telehealth (14 entries)</li>
<li>Adventist Health and Rideout (3 entries)</li>
<li>Allergy Associates</li>
<li>Ampla Health Chiropractic (Dr. Kinney)</li>
<li>Arbuckle Health Clinic (2 entries)</li>
<li>Avail Physical Therapy</li>
<li>Bartlett's Hearing Aid Center</li>
<li>Chico Eye Center</li>
<li>Chico Dermatology</li>
<li>Chico Hearing Aid Center</li>
<li>Chico Nephrology</li>
<li>Chico Physical Therapy Associates</li>
<li>CK Derm (2 entries)</li>
<li>Coast Physical Therapy</li>
<li>Colusa Health Clinic (6 entries)</li>
<li>Community Behavioral Health</li>
<li>Comprehensive Pain & Spine Center</li>
<li>Comprehensive Renal Care Group</li>
<li>Digital Hearing Aid Center</li>
<li>Dove's Landing (9 entries)</li>
<li>Dr. Harchetan Sandhu, MD</li>
<li>Dr. Douglas R. Myers, OD</li>
<li>Dr. Leena Singh, MD, PhD</li>
<li>Dr. Paramjit Singh, MD</li>
<li>Enloe (29 entries)</li>
<li>First Care Medical Associates (2 entries)</li>
<li>Glenn Medical Center (7 entries)</li>
<li>Healthy U Physical Therapy</li>
<li>Heart and Vascular Centers of America</li>
<li>Hodari MD & Rejuvene</li>
<li>Innovative Sleep Centers (3 entries)</li>
<li>Interventional Pain Solutions</li>
<li>Interventional Pain Physicians</li>
<li>Kokoro Counseling Center</li>
<li>Mindpath Health</li>
<li>North Valley Eye Care</li>
<li>North State Audiological Services</li>
<li>North State Pulmonary Associates</li>
<li>North State Sleep Center</li>
<li>Nysa Therapy</li>
<li>O Physical Therapy</li>
<li>Oroville Hospital and associated clinics (23 entries)</li>
<li>Oroville Eye Associates</li>
<li>Orland Physical Therapy & Sports Medicine</li>
<li>Oroville Podiatry Group</li>
<li>Orthopedic Associates of Northern California</li>
<li>Parkside Physical Therapy</li>
<li>Peach Tree Vision</li>
<li>Physical Therapy Associates of Oroville</li>
<li>Reeve Woods Eye Center</li>
<li>Retinal Consultants Medical Group</li>
<li>Stonebridge Counseling</li>
<li>Stabel Eye Clinic</li>
<li>Table Mountain Physical Therapy</li>
<li>The Growing Place</li>
<li>The Healing Center</li>
<li>Therapeutic Solutions</li>
<li>Valponi and Wagner</li>
</ul>

<li>Imaging/Labs:</li>
<ul>
<li>Adventist Health Feather River Lab and Medical Imaging</li>
<li>Enloe Advanced Imaging</li>
<li>Enloe Fountain Medical Imaging</li>
<li>Enloe Imaging (Main Campus)</li>
<li>HALO Precision Diagnostics & Breast Care</li>
<li>Oroville Hospital Imaging</li>
<li>Valley Medical Imaging</li>
<li>Valley Women's Imaging</li>
</ul>
</ul>

<h3>06/03/2024</h3>
Bug fixes:
<ul>
<li>Clicking in preferences menu area after opening and then closing menu no longer reopens menu.</li>
</ul>
New entries:
<ul>
<li>Added specialty providers: Enloe, Glenn Medical Center, Adventist Health Feather River, most of Oroville Hospital, most of Dove's Landing</li>
</ul>
