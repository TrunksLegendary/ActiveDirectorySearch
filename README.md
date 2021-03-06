<img align="left" src="https://raw.githubusercontent.com/aduguid/ActiveDirectorySearch/master/Resources/ADSearch.ico" width="64px">

# Active Directory Search
This Active Directory Search tool was written in Visual Studio Community 2017 C# Windows Forms and exports the results from LDAP to csv format. It uses LDAP (Lightweight Directory Access Protocol) to search Active Directory items from the treeview, the toolbar "Find" button or double clicking on the item in the listview.

<h1 align="center">
  <img src="Images/main_form.png" alt="MyApp" />
</h1>

## Table of Contents
- <a href="#dependencies">Dependencies</a>
- <a href="#glossary-of-terms">Glossary of Terms</a>
- <a href="#functionality">Functionality</a>

<a id="user-content-dependencies" class="anchor" href="#dependencies" aria-hidden="true"> </a>
## Dependencies
|Software                        |Dependency                 |
|:-------------------------------|:--------------------------|
|[Microsoft Visual Studio Community 2017](https://www.visualstudio.com/vs/whatsnew/)|Solution|
|[www.IconArchive.com](http://www.iconarchive.com/show/silk-icons-by-famfamfam.html)|Icons|
|[Snagit](http://discover.techsmith.com/snagit-non-brand-desktop/?gclid=CNzQiOTO09UCFVoFKgod9EIB3g)|Read Me|

<a id="user-content-glossary-of-terms" class="anchor" href="#glossary-of-terms" aria-hidden="true"> </a>
## Glossary of Terms
| Term                      | Meaning                                                                                  |
|:--------------------------|:-----------------------------------------------------------------------------------------|
|LDAP |Lightweight Directory Access Protocol|
|CSV |Comma-Separated Values|

<a id="user-content-functionality" class="anchor" href="#functionality" aria-hidden="true"> </a>
## Functionality
Listed below is the detailed functionality of this application and its components.  

####	Find Text (Dropdown)
* Lists all the values searched for in the current session

####	Find (Button)
* Queries Active Directory for the text in the "Find Text" textbox

#### Save (Button)
* Saves the current listbox view to a .csv file

####	User List (Button)
* This will change the layout of the listbox to show more information about each member of a group

####	Settings (Button)
* Opens the settings form. The domain name must be updated here.

####	About (Button)
* Opens the about form
