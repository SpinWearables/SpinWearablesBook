# The SpinWheel Fieldguide Booklet

Made with Scribus version 1.4.8.

## Making new pages

Use Page -> Insert Page to add new pages. Under "Master Pages", select "left_text" and "right_text"
New pages will not have text frames. Add a text frame and set it to be 7.5" high and 4.5" wide. The top left should be at (0.5", 0.5").
Link the text frame to the prior or next page as needed.


## Style guide and Scribus tips

Use the templated *story editor* for the majority of the text. It permits per-paragraph styling. Be careful with the use of the new-line/enter button (alt+enter can be used in the story editor to force new lines that do not force a new styled paragraph).

### Text

Use linked text frames on the main layer. 

Titles, headers of various levels, standard paragraphs are all done this way, with the story editor.

Inline code and other formating (such as refering to other pages) should be formatted using "Character Styles." To do this, open the properties window for the text frame, highlight the text, select "Text" -> "Style Settings" in the "Properties" window and select the desired Character Style

Inline math will have to be manually done, by overwriting the styling and using unicode math.

### Insets of various colors (intro, learn more, warnings)

A text frame with custom shape/fill/stroke on a separate layer.

### Math

The booklet contains very little math notation. For inline formulas we will use bolded unicode rendition when possible. When not, custom *render frames* can be used.

### Code

Inline code is boring monospaced as in the web page. Code panes might require custom *render frames* with exta LaTeX packages or images

### Images

Two extra layers for images, with properly set floating constraints.

### Flowing text around math/code/images

From properties, select shape and set text flow to countour line. You can edit the countour line from the edit button.

### Interface setup

Having the properties pane and the layers pane added to the default interface helps significantly.

# License

The copyright for this website, the online lessons, and printed materials belongs to SpinWearables LLC and so does the copyright for the code and hardware designs. All of these materials are permissively licensed: The website, lessons, and printed materials can be copied, remixed, and modified, as long as the purposes are non-commercial, attribution to the original creators is given, and any other constraints of the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License are fulfilled. Furthermore, the text (but not images and graphic artwork) of the teaching materials can be reused even for commercial purposes, under the Creative Commons Attribution-ShareAlike 4.0 International License. The code and hardware designs can be reused under similar conditions, even for commercial purposes, as long as the constraints of the GNU General Public License v3.0 are fulfilled.

The names “SpinWearables” and “SpinWheel” are trademarks of SpinWearables LLC. Derivative materials can use “inspired by SpinWearables/SpinWheel”, “based on SpinWearables/SpinWheel” or “for/compatible with SpinWearables/SpinWheel” phrasing, but can not use these trademarked names as a substring of their own names or otherwise claim they are endorsed by us.

If you have any questions, feel free to contact us. We are eager to ensure these materials are easy to share and extend in order to reach more curious minds.

