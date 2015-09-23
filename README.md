# Example of a pageflow form created with Bonita BPM 7
This sample presents a pageflow (or mutli-page) form created with Bonita BPM 7. This resulting form is equivalent to the pageflow form that existed in Bonita BPM 5 & 6.

## How does it work
The form relies on a ```page.current``` variable to store the current visible page.<br/>
All of the form's "pages" are stored in ```Container``` widgets and use their ```Hidden``` property to toggle their visibility based on the value of ```page.current```.<br/>
Custom buttons (a custom widget that triggers a JavaScript expression) are then added to each page to trigger the page change by increasing or decreasing the value of ```page.current```.<br/>

## Screenshots

Form in UI Designer<br/>
<p align="center"><img src="screenshots/pageFlow-in-designer.png"/></p>

Rendered form:<br/>
<p align="center"><img src="screenshots/pageFlow-rendered.png"/></p>
