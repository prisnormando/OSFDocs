.. _my-dashboard:

Dashboard
=========

**Purpose:** The Dashboard provides users quick access to their projects and allows them to create new projects. 

When logging in to the OSF, the dashboard is the default landing page.

When the user wants to navigate to the dashboard from another page on the OSF, they can do so by clicking **OSFHome** from the navigation bar.

In the top right of the dashboard, there is a green "Create new project" button. Clicking it allows a user to create a new project. A modal appears::
	
		Create new project
		Title
		Affiliation[Select all][Remove all]
		Storage location
		More
		[Cancel][Create]
		
The "Title" field is required but the other sections are optional. Affiliations associated with the user account will appear. Selecting an institution will add the affiliation to the project. The user's default storage location (United States by default, unless specified in the user's settings) will be selected by default. The user can click inside the menu to select a different storage location. Clicking **More** opens a drop-down section where the user can enter a description or select an existing project to use as a template for this new project. Helper text in the description field reads::
	
		Enter a project description
	
Helper text in the "Template" section reads::
	
		Start typing to search your projects. Selecting project as template will duplicate its structure in the new project without importing the content of that project.

Clicking **Cancel** returns the user to the dashboard without saving the project. Clicking **Create** creates the new project and prompts the following modal to appear::

	New project created successfully!
	[Keep working here][Go to new project]

Clicking **Keep working here** returns the user to the dashboard. Clicking **Go to new project** sends the user to the "Project Overview" page of their new project.

Below this green button is a search box with placeholder text that reads::
	
	 Search your projects 

Below the search box is a table displaying the 10 most recently updated projects and components on which the user is a contributor. If the user has more than 10 projects, there will be a down arrow that the use can click to show more projects. The arrow will show up to an additional 10 projects at a time. 

The user can type project/component titles and contributor names into the textbox to filter their projects (pressing "enter" is not necessary).

Below the search box is a sentence that reads::
	
	 Go to My Projects [links to the Project Organizer] to organize your work or search [link to https://osf.io/search/] the OSF 

The table of recently updated projects and components contains 3 columns: Title, Contributors, and Modified. The user can sort by date last modified (ascending or descending) and project or component title (ascending or descending) by clicking the up or down arrows in the table heading. 

Below the list of the user's projects is a section called "Discover Public Projects." In this section, there are two columns: "New and Noteworthy" and "Most popular." Each contains links to 5 public projects on the OSF. Below this is a button, "Search for more projects," which takes the user to osf.io/search

Below this section is a marketing section that displays information about OSF for Meetings and Preprints. This section can be used to highlight other products or initiatives. This section appears as follows::
	
		Hosting a conference or meeting?
		Use the OSF for Meetings service to provide a central location for conference submissions. [View meetings]
		
		Browser the latest research
		Check out the latest Preprints hosted on the OSF covering a variety of research areas. [View preprints]

.. include:: include/organizer.rst
