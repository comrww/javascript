## CSS Structure

  <a name="css_structure--basic"></a><a name="NR3.1"></a>
  - [NR3.1](#types--basic) **Basic Structure**: All CSS should follow the structure below


    ```css

    /***************************** YES *****************************/
     1|.example_class_name {
     2|	color: red;
     3|	background-color: grey;
     4|	border: solid 5px black;
     5|}
	 6|
	 7|.example_class_name_two {
     8|	color: blue;
     9|	background-color: white;
    10|	border: solid 5px black;
    11|}
    12|

	/***************************** NO *****************************/
	  1|.example_class_name {
      2|	color: red;
      3|	background-color: grey;
      4|	border: solid 5px black;
      5|}
      6|.example_class_name {
      7|color: red;
      8|background-color: grey;
      9|border: solid 5px black;
     10|}
     11|.example_class_name_two {color: blue; background-color: white; border: solid 5px black}
    ```

  <a name="css_structure--return"></a><a name="NR3.2"></a>
  - [NR3.2](#css_structure--return) **Return**: All CSS classes should be followed by one return (a blank line). 

  <a name="css_structure--indentation"></a><a name="NR3.3"></a>
  - [NR3.3](#css_structure--indentation) **Indentation**: CSS properties should appear on the line below the selector (i.e class / id /...) and should be indented by a single tab. 

  <a name="css_structure--format"></a><a name="NR3.4"></a>
  - [NR3.4](#css_structure--format) **Spacing**: SASS should be limited to three layers of depth. When using SASS and LESS try to create reusable structures that can be applied to future projects. 

  <a name="css_structure--placing"></a><a name="NR3.5"></a>
  - [NR3.5](#css_structure--placing) **Placing CSS**: You should take a scoped approach when placing new CSS. If the property that you are trying to add needs to be reused across multiple widgets, you should place the property in a class on the theme. If the property is only used once within the scope of a single widget, you should place the property within a class in the CSS for that specific widget. 

  <a name="css_structure--gvar"></a><a name="NR3.6"></a>
  - [NR3.6](#css_structure--gvar) **Global Variables**: Global variables should be placed directly on the theme itself. Globally used CSS should not be written directly on the theme, but should however be written inside of a separate CSS file associated with the theme. 

  <a name="css_structure--breakpoints"></a><a name="NR3.7"></a>
  - [NR3.7](#css_structure--breakpoints) **Breakpoints**: There are five standard breakpoints built into Bootstrap, each is associated with a size. They are listed as follows: 

  ```
  xs - 320px,  
  sm - 480px, 
  md - 768px, 
  lg - 992px, and 
  xl - 1200px
  ```

  <a name="css_structure--cname"></a><a name="NR3.8"></a>
  - [NR3.8](#css_structure--cname) **Adding Class Names to Elements**: A class name should only be added to an element whenever properties within an existing class or a new class need to be applied to a given element. 

  <a name="css_structure--dry"></a><a name="NR3.8"></a>
  - [NR3.8](#css_structure--dry) **Dont Repeat Yourself**: A class name should only be added to an element whenever properties within an existing class or a new class need to be applied to a given element. 