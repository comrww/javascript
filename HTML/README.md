

## HTML Structure

  <a name="html_structure--layers"></a><a name="NR2.1"></a>
  - [NR2.1](#html_structure--layers) **Commenting**: If a block of HTML is more than 7 layers deep a comment should appear above the block which clearly outlines its purpose, a comment should also appear after the last closing tag which contains the prefix “end” followed by a space and the name of the class or id associated with its opening tag. 

  <a name="html_structure--helpers"></a><a name="NR2.2"></a>
  - [NR2.2](#html_structure--helpers) **Bootstrap Helper Classes**: Bootstrap helper classes should be used whenever possible (i.e. instead of adding padding to an element the Bootstrap wrapper class should be used). 

<table>
	<thead>
		<th colspan="2">
			Here is a list of available helper classes in Twitter Bootstrap:
		</th>
	</thead>
	<tbody>
		<tr>
			<td>Padding:</td>
			<td><strong>wrapper, wrapper-xs, wrapper-sm, wrapper-md, wrapper-lg, wrapper-xl</strong></td>
		</tr>
		<tr>
			<td>Horizontal Padding:</td>
			<td><strong>padder, padder-xs, padder-md, padder-lg, padder-xl</strong></td>
		</tr>
		<tr>
			<td>Vertical Padding:</td>
			<td><strong>padder-v, padder-v-md, padder-v-lg, padder-v-xl</strong></td>
		</tr>
		<tr>
			<td>Top Padding:</td>
			<td><strong>padder-t, padding-top-s, padding-top-m, padding-top-lg, padder-t-lg, padder-t-xl</strong></td>
		</tr>
		<tr>
			<td>Right Padding:</td>
			<td><strong>pad-right</strong></td>
		</tr>
		<tr>
			<td>Bottom Padding:</td>
			<td><strong>padder-b-none, padder-b, padder-b-md, padder-b-lg, padder-b-xl</strong></td>
		</tr>
		<tr>
			<td>Margin:</td>
			<td><strong>m, m-n, m-t-xxs, m-t-xs, m-t-sm, m-t-lg, m-t-xl, m-t-n-lg</strong></td>
		</tr>
		<tr>
			<td>Top Margin:</td>
			<td><strong>m-t, m-t-none, m-t-xxs, m-t-xs, m-t-sm, m-t-lg, m-t-xl, m-t-n-xs, m-t-n-lg</strong></td>
		</tr>
		<tr>
			<td>Right Margin:</td>
			<td><strong>m-r, m-r-none, m-r-xs, m-r-sm, m-r-lg, m-r-n</strong></td>
		</tr>
		<tr>
			<td>Bottom Margin:</td>
			<td><strong>m-b, m-b-none, m-b-xs, m-b-sm, m-b-lg, m-b-xl, m-b-n</strong></td>
		</tr>
		<tr>
			<td>Left Margin:</td>
			<td><strong>m-l, m-l-none, m-l-xs, m-l-sm, m-l-lg, m-l-n</strong></td>
		</tr>
		<tr>
			<td>Text Color:</td>
			<td><strong>text-muted, text-primary, text-success, text-info, text-warning, text-danger</strong></td>
		</tr>
		<tr>
			<td>Background Color:</td>
			<td><strong>bg-primary, bg-success, bg-info, bg-warning, bg-danger</strong></td>
		</tr>
		<tr>
			<td>Float Elements</td>
			<td><strong>pull-left</strong> - Floats an element to the left<br>
			<strong>pull-right</strong> - Floats an element to the right</td>
		</tr>
		<tr>
			<td>Clearing Floats</td>
			<td><strong>clearfix</strong> - Clears floats</td>
		</tr>
		<tr>
			<td>Display & Margin</td>
			<td><strong>center-block</strong> - Sets an element to display:block with margin-right:auto and margin-left:auto</td>
		</tr>
		<tr>
			<td>Visibility</td>
			<td><strong>show</strong> - Forces an element to be shown (display:block)<br>
			<strong>hidden</strong> - Forces an element to be hidden (display:none)<br>
			<strong>invisible</strong> - Forces an element to be invisible (visibility:hidden). Will take up space on page even though it is invisible<br> 
			<strong>sr-only</strong> - Hides an element to all devices except screen readers<br>
			<strong>sr-only-focusable</strong> - Combine with "sr-only" to show the element again when it is focused (e.g. by a keyboard-only user)<br>
			<strong>text-hide</strong> - Helps replace an element's text content with a background image<br>
			<strong>close</strong> - Indicates a close icon<br>
			<strong>caret</strong> - Indicates dropdown functionality (will reverse automatically in dropup menus)</td>
		</tr>
		<tr>
			<td>Hide</td>
			<td><strong>visible-xs, visible-sm, visible-md, visible-lg</strong></td>
		</tr>
		<tr>
			<td>Show</td>
			<td><strong>hidden-xs, hidden-sm, hidden-md, hidden-lg</strong></td>
		</tr>
	</tbody>
</table>


  <a name="html_structure--append"></a><a name="NR2.3"></a>
  - [NR2.3](#html_structure--append) **Writing New CSS**: Append Bootstrap classes when possible. When it is absolutely necessary to apply additional css properties to an element, do so by selecting an existing bootstrap class which is being used in the DOM and append it with additional properties. 

  <a name="html_structure--containers"></a><a name="NR2.4"></a>
  - [NR2.4](#html_structure--containers) **The Bootstrap Container Class**: Avoid using the container class. The container class is utilized by the serialization process in ServicePortal. Avoid using this class on all elements with the exception of the footer. Never apply classes to containers, rows or columns unless you are overriding bootstrap layout classes. 

  <a name="html_structure--div_rule"></a><a name="NR2.5"></a>
  - [NR2.5](#types--div_rule) **New Widget Markup Requirement**: All of the HTML markup for a specific widget must be contained within ``` “<div></div>” ``` tags. 



