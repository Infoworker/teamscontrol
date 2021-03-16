# Release notes March 16, 2021

## Features and improvements

### Overview & Control End users, Owners and Approvers
-  Added possibility to onboard users to Microsoft 365 Groups, Teams, Sharepoint sites from details page.

### Fixes
-  Fixed updating group settings from details page. Now it is not possible to update settings if group/team name is empty and Org-wide visibility was removed from possible choices for visibility field. Both issues caused update settings to fail.

# Release notes March 11, 2021

## Features and improvements

### Overview & Control End users, Owners and Approvers
-  Added configuration of OneNote and Tasks by Planner and To Do tabs. Now if user creates/updates channel or creates team with channels containing one of those tabs, tabs are autoconfigured and user doesn't need longer to manually configure those tabs via Teams. For each OneNote tab is created its own Notebook and for each Tasks by Planner and To Do tab is created its own Planner plan.

### Fixes
-  Added check for channels names in templates settings and details page in order to could not update/create channels with existing/same channels names to avoid error while creating/updating teams.
-  Fixed showing number of users in groups overview and details page.
-  Fixed changing of tab display name in templates settings (add/edit channel in channel settings in teams settings) and details page (create/edit channel).

# Release notes March 10, 2021

## Features and improvements

### Fixes
- Sign out from web will only sign you out from the tab, not Teams
- No longer possible to send new requests with external users as owners or members when "Allow adding guests to the team" setting is turned off.


# Release notes March 8, 2021

## Features and improvements

### Teams Control Admins
-  In template settings was removed possibility to reuse subconfigs (Input field settings), before it was possible to choose another existing Input field settings. Feature was removed according to its uselessness and to avoid overcomplexity of operations with templates.

### Fixes
-  Minor fixes.


# Release notes March 4, 2021

## Features and improvements

### Overview & Control Admins
-  Added visitors field to template settings (Microsoft 365 Groups type templates).

### Overview & Control End users, Owners and Approvers
-  Added visitors field to New request form for Microsoft 365 Groups type templates.

### Fixes
-  Language support in tabs on mobile devices (English, Norwegian).
-  Fixed loading of New request form for Microsoft 365 Groups type templates that had "Requester as default owner" setting toggled for Owners field in Input field settings in template settings.


# Release notes March 3, 2021

## Features and improvements


### Overview & Control Admins

- Admins are now able to see an overview of all users access across the tenant.
  * The overview contains the following views; ; All users, Internal users, External users and No membership. 
  * The list shows the users names, team they are owners of, members of, and where they are guests. 
  * Possiblity to look up users using search functionality
  * Added buttons to easily onboard users, and add external users
- Added overview of all templates available with the possibility
  * Filter by status, approval and provisioning type. 
  * Edit and delete templates
- Admins can now control what Teams, Grops or SharePoint sites end users are able to see in the overview list. 
- Settings - User Access
  * Added icon for users with disabled accounts (blocked sign-in).
  * Filter is extended with category "Blocked user" that allows to get just blocked users of organization.
  * Onboarding of blocked users is limited so that it is not possible to onboard users of this type to SharePoint sites and as visitors to Microsoft 365 Groups.
- Settings - Overview
  * Added Overview button that navigates to Overview settings.
  * Overview settings allow to configure what non-administrator users see under Overview tab, making possible to filter Overview items based on status and type and set default sorting parameter. In addition admin user can restrict view so that for end user are visible just groups/teams/SP sites where user is member or owner

### Overview & Control End users, Owners and Approvers

- End users can now get an overview of all Teams/Groups in the organization
  * View all Teams/Groups, where the user is a member, or where the user is an Owner
  * Filter by Status and Type
- Added mouseover tooltip describing each template when users requests a new team, to make sure they choose correct template
- Group/Team/SP site Details (preview)
- Settings were extended with Visibility and Guest access fields that can be changed
- In details for team were added extra features that allow to install new apps, create, update and delete channels, change status and edit settings
- Added icon for blocked users


### Fixes
- Minor fixes


# Release notes February 27, 2021

### Fixes
-  Small changes in details page in order to improve performance.
-  Fixed showing of correct icons and tooltips for users in details page.


# Release notes February 25, 2021

### Fixes
-  Fixed error that prevented opening details page of some groups and SP sites.


# Release notes February 24, 2021

## Features and improvements

### Overview & Control Admins
-  User access page functionality was changed from loading all users at a time to loading just 20 users at a time in order to improve performance. It was added "Load more" button that allows to load 20 more users and so on. It is also possible to narrow down number of found users using filter that contains categories All users, Internal users and External users and search field, changing each of mentioned parameters will show top 20 users according to values of these parameters.

### Fixes
-  Minor fixes.

See <a href="https://teamscontrol.com/app/uploads/2021/03/Product-Sheet-Overview-Control.pdf" target="_blank">Product Sheet</a> for all features and functions.