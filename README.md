sublime-text-2-addon
====================

some useful "snippet, build" addons for sublime text 2 text-editor, pick up if you feel useful, too.


##snippet 

### 1.angularjs.sublime-snippet

**Decription**

generate angularjs js includes <br>

***

**[detail]** <br>

keyboard shortcut : __ type "angularjs" then press tab__ <br>
scope :  <b> *.html </b>

### 2.doctype.sublime-snippet

**Decription**

generate basic html5 tags <br>
( with angularjs/bootstrap css tag )
***

**[detail]** <br>

fillup: $1=> title, $2=>description, $3=> container html  body<br>
keyboard shortcut : __ type "doctypes" then press tab__ <br>
scope :  <b> *.html </b>

### 3.gistblogger.sublime-snippet

**Decription**
generate gist codesnippet for blogger

(notice)

"gist-blog" javascript library only need to load once, if there is another chunk of code just copy generated gist-code part. watch out if the "data-file" info must be fillup exactly match to gist, or it will fail to load rest parts.

***

**[detail]** <br>

fillup: $1=> data-id, $2=> gist-id, $3=> data-filename<br>
keyboard shortcut : __ type "gistblog" then press tab__ <br>
scope :  <b> *.html </b>


##build

###1.chrome-preview.sublime-build

**Decription**

Let chrome browser open the page you're editing, preview it.
***

**[detail]** <br>
scope :  <b> *.html </b>