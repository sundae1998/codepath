While signed in as admin, I entered a cross site script text in the body of the comment section. The text goes as follows:" <INPUT TYPE="BUTTON" ONCLICK="alert('XSS')"/>
This created a button in my comment.After submitting, the post was converted to a button which when clicked on made an alert appear at the top of the page. 
This was located on the wordpress 4.2 version.
Image of alert received attached as xss_word_press_vulnerability.png

The second exploit was with editing the name of the of the widget. 
When cross site script text was entered in place of a name, it created a button that made a an alert appear. 
This demonstrates a vulnerability in the widget names.
Image of alert received attached as xss_widget_vulnerability.png
