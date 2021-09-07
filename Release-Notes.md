# Release notes September 3, 2021

### Fixes
- Details page - fixed error with updating description that contains line breaks. 

# Release notes August 27, 2021

### Overview & Control End users, Owners and Approvers
- It was added more user information in corresponding user input fields. Now when trying to find user it is shown user display name, user email and job title (if it is defined in AD), 

# Release notes August 26, 2021

### Overview & Control End users, Owners and Approvers
- It was added functionality that allows to onboard MS 365 groups as owners/members/visitors to groups/teams/sites via details page and as part of provisioning.
- It was added Sensitivity label field to new request form of SharePoint Communication site templates (showing of field must be enabled in corresponding templates settings) that allows to assign Sensitivity label to provisioned site (if it is allowed in tenant).

### Teams Control Admins
- It was added functionality that allows to add MS 365 groups as owners/members/visitors in template settings.
- It was added Sensitivity label field to input field settings section of SharePoint Communication site templates that allows to choose sensitivity label that will be assigned to provisioned site (if assign label is allowed in tenant).


# Release notes August 19, 2021

### Teams Control Admins
- Added check for Allow add guests and Sensitivity label fields. Check is based on tenant level group settings and is intended for limiting "allow add guests" and "assign sensitivity label" functions. If tenant group settings doesn't allow to add guests or assign labels, corresponding input fields will be disabled in template settings, request form and details page.

### Fixes
- Fixed change input fields data in details page bug. 

# Release notes August 18, 2021

### Fixes
- Assign sensitivity label functionality was improved and now is more stable. It concerns assigning sensitivity label as part of group/team provisioning and group/team update via details page. 


# Release notes August 17, 2021

## Features and improvements

### Overview & Control End users, Owners and Approvers
- It was added sensitivity label field to group/team request form (if corresponding field is allowed to be shown in request in corresponding provisioning template) and group/team details page. Now user can see available sensitivity labels of organization (if some are created for organization) and assign label to group/team (if organization has minimum Azure Premium P1 license). Despite it Overview table was extended with Sensitivity label field.
- Users have now the possibility to provision SharePoint Communication sites (if corresponding SP Communication site templates are created).
- For educational tenants - users can now provision educational teams of types Class, PLC and Staff (if corresponding templates are created). This functionality is available only if tenant is educational.


### Teams Control Admins
- It was added sensitivity label field to template settings. Admin can see available sensitivity labels of organization (if some are created for organization) and choose sensitivity label in template settings (organization should have minimum Azure Premium P1 license to could assign label to group/team). 
- SharePoint Communication site was added as available template type. Admin users can now create SP Communication site templates and define Communication site provisioning options such as site address, hub association, default language, time zone, external sharing settings, theme, header, footer and navigation look and folder structure in Documents library.
- Team/Group templates were extended with SharePoint settings section that allows to define settings of SP site team/group is connected to. User can define such settings as external sharing settings, hub site connection, theme, header and folder structure in Documents library.
- It was implemented SP site customization background job. Purpose of this job is to customize header, footer, navigation and some parts of external sharing settings that can't be customized immediately after SP site is provisioned. Job runs 30 minutes after SP site is provisioned and is a final stage of SP site customization.
- For educational tenants - Class, PLC and Staff were added as available types of Team templates. These team types are visible only if tenant is educational.

### Fixes
- It was fixed filtering of external/blocked users in user input fields (Owners/Members/Visitors fields) in template settings, request form and details page. Now if adding of external users is limited by template/group settings, external users can't be found in user input fields. Before this functionality user could find external users, but received an error message if adding of external users was limited. When it comes to SP Communication site user fields and visitors field of MS 365 Group, it is now limited adding of blocked users. 
- Fixed setting of Giphy content rating (part of Fun settings in Team settings).

# Release notes June 15, 2021

## Features and improvements

### Overview & Control Admins
-  For new customers was added contact form that is mandatory to be filled. After installing application for first time and giving consent to all necessary permissions user will be forwarded to contact form. After submitting the form user will be forwarded to tab content and can start to use application. Filling the form is need in order to could contact new customers and control duration of trial period.

# Release notes June 2, 2021

### Fixes
- Better support for dark mode
- Small fix in details page update flow
- Other minor fixes


# Release notes May 27, 2021

### Fixes
- Fixed bug where some templates in new requests don't show
- Fixed team/group provisioning flow bug that caused crush of whole flow in case of error during authentication against Sharepoint.


# Release notes May 26, 2021

## Features and improvements

### Overview & Control Admins
-  Edit template page was extended with visibility settings that allow to define users that are allowed to use template in New request page. Users can be defined based on users Azure Id, AD group user is owner/member of and other users AD data, such as company name, department, office, country and state.

### Overview & Control End users, Owners and Approvers
-  In New request page are shown just templates that are available for user based on visibility settings configured in template settings.

### Fixes
-  Minor fixes

# Release notes May 20, 2021

### Fixes
- Fixed empty checkboxes in User access page.

# Release notes May 18, 2021

### Fixes
- Fixed Delete request form missing buttons bug.
- Minor fixes in request details page.

# Release notes May 15, 2021

## Features and improvements

### Overview & Control End users, Owners and Approvers
-  Create request functionality was modified so that now when clicking New request button user is navigated to the page for request creation instead of popup window as was before. New request page has more friendly interface and consists of several stages of creating a request. All templates are listed under first stage with description and other details that give user more information about templates than before, in addition it is possible to search and filter templates.

- Request overview - Open request functionality was modified so that now user is directed to request details page when clicking Open request. Page contains team/group provisioning data, template description, request status and info button. Clicking on the info icon opens popup window that contains request details, error messages if request was created with errors and log that shows history of request status change with date, status, comments and person name that changed status of request (e.g. approved/rejected request etc.).
- Request overview - was added Delete request action, request can be deleted only if it has status Awaiting approval.

### Fixes
- Create request - team/group name validation was improved and is now more correct than before.
- Fixed disappearing of creation date and comment field from requests overview after approve/reject request.
- Minor fixes.



# Release notes April 15, 2021

## Features and improvements

### Request overview
- New design for request overview. All the requests are now in one list and can be filtered on status. 
- Added search field for requests. 
- If you are an ordinary user, you will only see the view "My requests". 
- If you are an approver of a template, you will also get a view for "My approvals".
- Admin user can now se all the requests in the tenant and can approve/reject requests even though he/she is not an a approver for the corresponding template.
- Added view for failed requests for Admin users. Admin user can now se requests that are created with errors or failed. 

### Fixes
- Minor fixes.

# Release notes April 8, 2021

## Features and improvements

### Overview & Control End users, Owners and Approvers
-  Details page was extended with functionality that allows to change role of user (owner/member/visitor) or remove user completely from group/team/SP site. In addition it was also added a "Leave group" button that allows logged in user to leave group/team/SP site if user is member/owner/visitor of it.
-  It was added tooltip (info icon) for input fields in New request form, tooltip is visible for the input field if admin user added tooltip in Template settings.
-  Added functionality that allows to handle channel folders in Edit channel form in Details page.
-  It was changed submit process of request approval or request that doesn't need approval. Now user doesn't need to wait until all processes are finished to get success message, success message appears immediately and all team/group creation processes run in the background. User gets a notification in Teams when team is created (in case of team creating), it is also possible to check status of submitted request under requests overview in order to be sure that team/group is created.

### Teams Control Admins
-  It was added Custom tooltip setting for each field in Input field settings in Template settings, it is accessible via choosing More settings of target field. Custom tooltip setting is needed in order to end users could know how to fill input fields in New request form.

### Fixes
- Added hover text for buttons in the top right corner on the details page. For example "Go to team". 
- Minor fixes.

# Release notes March 24, 2021

### Fixes
-  Fixed update Overview settings bug.
-  Removed red stars that indicate which fields are mandatory in Input field settings in Template settings, so that user is not confused that these fields should be filled in Template settings, however mandatory fields are still marked with red stars in New request form.

# Release notes March 23, 2021

## Features and improvements

### Overview & Control Admins
-  Overview settings were extended with extra fields that allow to limit access to create new group/team request from Overview. It is possible to choose one of three user categories - All users, Only global admin and teams admin users and Custom. When choosing Custom it appears an input field where admin can specify who can have access to create new requests, it can be either user or AD group.

# Release notes March 22, 2021

## Features and improvements

### Fixes
- The pop-up window for consenting app permissions when the app is installed  will no longer be blocked in Chrome browser
 

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

### Overview & Control Admins
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