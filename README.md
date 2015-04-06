# angular-metro-ui
AngularJS Implementation of Sergey Pimenov's Metro UI CSS 2.0 Framework

About This Project
----------
This project was created to allow easy use of Sergey Pimenov's Metro UI CSS 2.0 Framework in AngularJS Applications. In addition to the main goal, this project will also implement a method for users to write mock xml code for the Fluent Ribbon plugin of the Metro UI Framework.

This implementation is intended to satisfy the needs of (likely) a small group of developers, including myself, who are developing web applications using AngularJS, but would like to maintain the Metro UI that many of our customers' and/or our own business' end users are familiar with. I honestly find the visual presentation of frameworks that use Google Material Design (and some other design principles) to be more ascethically pleasing.  However, the familiarity of things like the Fluent Ribbon for many of my company's end users is a big when introducing new software to them.

I hope others out there will find this port of Metro UI useful. Of course, I would like to thank Sergey Pimenov for doing all of the heavy lifting and creating the original framework. 

Fluent UI and Mock Ribbon XML
----------
Anyone who has done even minor UI development in Microsoft Office Applications is familiar with Ribbon XML. This project will allow developers to directly port their knowledge of Ribbon XML into projects using this framework. In the stand alone framework, to create a ribbon, you have to create a ul of tabs and then a div object for the content of each tab.  In this implementation, developers will be able to compose thier ribbons in a syntax that is nearly identical to native ribbon xml, i.e.

```html 
<fr-tab>
  <fr-group>
    <fr-button/>
  </fr-group>
</fr-tab>

```
The "fr-" is used to avoid any confusion between Ribbon XML tags that might conflict with normal HTML tags, such as <button>

Progress
-----------
Well, I just created this repository today (4/6/2015). I will update this readme as I complete more work on this project.
