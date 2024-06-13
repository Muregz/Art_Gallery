###### Website
- website : generally consists of static content that is delivered as a user request it. 
- Mostly informational 
- blog pages , company landing pages , portfolios 

###### Web applications
- Are interactive and dynamic 
- provide users with functionalities like form inputs , dashboards , content management systems. 
e.g. ecommerce pages, banking systems , social media platform 

The backbone of any webpage is HTML . (HyperText Markup Language)
###### HTML 
defines the structure and content of a webpage 

1. Define the content structure : HTML uses tags / elements to define the structure(the latyout and the content a user can see , paragraph, button , image , video) of the webpage 

syntax of HTML
-
<> : opening tag  </> : closing tag
 say a paragraph <p> content </p>
                 <button> title of the button </button>

- </> closing tag
say img <img/>
     br <br/>  : <br>


2. Semantics: HTML provides semantics tags that provide specific meaning to content : Search Engine Optimization : 
<header></header> : heading section of the webpage
<footer></footer> : defines the bottom section of a page 
<nav></nav> : navigation

3. Hyperlinks : HTML allows the linking of pages, external resources and internal resources through hyperlink tags  <a> tag : anchor tag , <link>

4. Forms and Inputs : Collect user input and interact with backend services 
<form>
   <input/> email
   <input/> password
   <button>Login<button>
</form>

comment tags are used to write notes with coding scripts. 
<!-- write comment -->

###### CSS (Cascading Style Sheets)
- used to style and layout the web content structured by HTML

1. Design and layout : Controlling the visual appearance of a page 
2. Responsive Design : CSS will allow us to adapt to different screen sizes and devices making the content accessible through all platforms 
: media queries and flexible grid layouts 
3. Animations and Effects : creating visual effects (transitions) : JS is more friendly. 

Syntax of CSS 
Selectors  : Element Name (p,button) , elements id (#nameofid) , class selector ( .nameofclass )

selector {
    stylingproperty : value
}

p {
    color: red;
}

