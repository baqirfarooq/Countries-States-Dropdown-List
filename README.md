# Country & State Dropdown List JavaScript library
###### A JavaScript library to create country &amp; state dropdown lists containing all the country names and state names.

##### How to Use:

##### In Head/Footer section:
`<script type= "text/javascript" src = "countries.js"></script>`

##### In Body Section:

**Select Country Dropdown**  
`<select onchange="print_state('state',this.selectedIndex);" id="country" name ="country"></select>`

**Select City/State Dropdown**
`<select name ="state" id ="state"></select>`

**Initialize Library Script**
`<script language="javascript">print_country("country");</script>`
