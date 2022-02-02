# Release notes February 2, 2022

### Fixes
- Fixed onboard security groups to SharePoint sites and as visitors to MS365 groups via details page and request form.
- Fixed onboard MS365 groups to SharePoint sites and as visitors to MS365 groups as part of site/group provisioning.

# Release notes January 31, 2022

### Fixes
- Minor fixes.

# Release notes January 28, 2022

### Fixes
- Fixed handling of security groups that can possibly be members of MS365/security groups. Fix concerns onboarding MS365/security groups as owners/members to groups/teams via request form or details page.

# Release notes January 27, 2022

### Overview & Control Admins
- It was added Integrations page to Settings tab. Integrations page contains currently only Documaster integration input form so that users who will take in use Documaster archive functionality can use this form to connect to Documaster API. After successfully connecting it will be added Documaster integration section to all templates where user can define archive structure. Defined archive structure will be also shown in details page of group provisioned with template that has enabled archive structure.
- Teams settings section in template designer was improved with copy OneNote notebook and Planner plan functionality. This functionality is available in Tab settings section of Create channel/Edit channel form. When adding OneNote or Tasks by Planner and To Do tab user will be able to either create new Planner/OneNote or copy from existing. To be able to copy from existing OneNote/Planner user should know which group/team existing OneNote/Planner belong. User should first enter group name and choose corresponding group in search field and then click Search button to find notebooks/plans that this group contains.

### Overview & Control End users, Owners and Approvers
- Moved "New Request", "View Requests" and "Export for Excel" buttons to a compounded button "Actions" to improve user experience
- Incoming requests now appears as a notification at the top of screen
- Minor styling updates to Quick Details

### Fixes
- Fixed some bugs concerning onboarding groups as owners/members of groups/teams and private channels.

# Release notes January 20, 2022

### Overview & Control End users, Owners and Approvers
- It was added possibility to onboard groups to private channels in team request form if corresponding template team settings allows defining private channel owners and members.
- Implemented new styling to trial message bar, updated links

### Fixes
- Minor fixes.

# Release notes January 19, 2022

### Fixes
- Minor overview and details page UI changes.

# Release notes January 17, 2022

### Overview & Control End users, Owners and Approvers
- Group/team/site details page user interface was improved for better performance. It was added separate tabs for each category - "General" tab contains general group info such as name, description, last activity date etc., "Users" tab allows to handle group users (onboard, offboard, change user role), "Logs" tab provides details page action history, each log contains name of user that performed action, timestamp and action name. Team details page contains several additional tabs such as "Channels" that allows user to handle team channels, "Apps" where user can install/uninstall team apps and "Team settings" where owners and admin users can handle team settings.
- The overview list received a new functionality named quick details. Clicking on a team/group/site in the overview list will open a drop down and give the user a more refined look at the team/group/site details. 
- Limited onboarding blocked users as private channels members in team request form.

### Fixes
- Fixed overview search that hasn't worked as it should after performing group actions (delete, archive etc.).
- Fixed Request settings bug that caused issues with New request button visibility for users added to Custom section of Request settings.



# Release notes December 10, 2021

### Overview & Control Admins
- Template designer was improved with functionality that allows user to define how users should be onboarded to private channels in Teams settings section. Possible choices are to onboard team owners as channel owners, onboard team owners and members as channel owners and members respectively or specify channel owners and members in request form.

### Overview & Control End users, Owners and Approvers
- Request form was extended with possibility to specify owners and members of team private channels (if it is chosen corresponding option for corresponding channel in template designer).

### Fixes
- Fixed showing several approvers in requests overview bug.
- Fixed line break bug when showing display name with prefix and suffix in request form.


# Release notes December 3, 2021

### Fixes
- Fixed several typos in user interface.

# Release notes December 2, 2021

### Fixes
- Fixed requests overview undefined approvers and requesters bug.

# Release notes December 1, 2021

### Fixes
- Fixed showing user email data for users that doesn't have assigned email in user search input fields.
- Fixed sorting requests overview table by template column.

# Release notes November 24, 2021

### Fixes
- Fixed some dark theme bugs.

# Release notes November 22, 2021

### Fixes
- Fixed import SharePoint sites bug.

# Release notes November 18, 2021

### Fixes
- Fixed last activity date column sorting in Overview.
- Fixed bug with navigating to request overview after request create or reject.

# Release notes November 16, 2021

### Fixes
- Fixed bug with choosing users for user custom field in template settings and request form.


# Release notes November 15, 2021

### Fixes
- Fixed bug with choosing options for multiselect dropdown custom field in template settings and request form.
- Fixed bug with updating request status after request rejection.

# Release notes November 12, 2021

### Overview & Control End users, Owners and Approvers
- Date column name in Overview was changed to Last activity and now shows group/team/site last activity date.

# Release notes November 10, 2021

### Fixes
- Fixed bug with user fields validation in request form that allowed user to submit request while mandatory user fields were empty.
- Fixed bug with showing owners data in new request form that haven't been shown correctly if "Requester as default owner" setting of owners field in corresponding template was on.

# Release notes October 27, 2021

### Fixes
- Minor fixes.


# Release notes October 28, 2021

### Overview & Control Admins
- Details page - it was removed restriction on performing operations with Teams apps and channels tabs. This functionality was available only for users that have global administrator role. Now this functionality is available also for team owners and members (if team settings allow members to manage apps/tabs).


### Overview & Control End users, Owners and Approvers
- Template settings - managing Teams apps and tabs is now allowed for Teams administrators (was allowed only for global administrators before).

### Fixes
- Fixed disabled Approve button for some requests bug.
- Fixed creating groups that contain more than 20 users bug.

# Release notes October 27, 2021

### Fixes
- Minor fixes.


# Release notes October 20, 2021

### Fixes
- Fixed bug with creation of default Notebook as part of team provisioning. 
- Fixed showing of custom fields in request form if custom fields are switched off in corresponding template settings. 
- Fixed some validation errors in add custom field form in template settings.


# Release notes October 19, 2021

### Fixes
- Fixed saving data in Overview settings and Request settings that didn't work as it should. 


# Release notes October 18, 2021

### Overview & Control Admins
- It was added settings icon to Settings tab. Settings icon contains Sign out action.
- It was added settings icon to Overview tab. Settings icon contains actions that allow user to sign out from application, import groups, navigate to Overview settings page and Request settings page. Import groups, navigate to Overview settings page and Request settings page were removed from Settings tab and now are located only under settings icon under Overview tab.

### Overview & Control End users, Owners and Approvers
- It was added settings icon to Overview tab. Settings icon contains Sign out action.

### Fixes
- Added one more fix for Limit who can submit requests section in Manage overview & request page that didn't work as expected concerning handling of groups added to Custom field.
- Fixed dark mode behavior under request details page. 
- Fixed editing naming policy under template settings bug.



# Release notes October 12, 2021

### Fixes
- Fixed initializing new request form that didn't show any input fields but just loading.
- Fixed adding several contacts in Company information page.

# Release notes October 11, 2021

### Overview & Control Admins
- Template settings - it was added Custom fields section under Input field settings that allows to define custom fields of different types. Custom fields don't affect any data in AD and are suitable for providing extra data for request or provisioned group and exist only as part of application.
- Settings tab was extended with Company information page where user can change company and contacts information (concerns modifying data that user provided when filling contact form when installing application for first time). Despite it user is provided with read-only tenant info that includes tenant type, tenant id and tenant-wide group settings. Each group setting has description that is shown when hovering on info button and link to tutorial about updating setting or place where user can update setting when clicking info button.  


### Overview & Control End users, Owners and Approvers
- New request form - it was added Custom fields that allow to provide more info about created group (if custom fields are activated for corresponding templates and marked as visible in request). 

### Fixes
- Fixed dark mode behavior under New template page. 
- Performed fix for Limit who can submit requests section in Manage overview & request page that didn't work as expected concerning handling of groups added to Custom field.


# Release notes October 4, 2021

### Overview & Control End users, Owners and Approvers
- It was added Export for Excel button to Overview page. Clicking button allows to export all data that is currently shown in Overview to Excel file that is downloaded to default folder for downloaded files.  


# Release notes September 30, 2021

### Overview & Control Admins
- Template settings - connect to hub functionality was moved from SharePoint settings to input field settings.
- Template settings - input field settings section was extended with register site as hub functionality.

### Overview & Control End users, Owners and Approvers
- New request form - it was added possibility to connect site to hub and to register site as hub as part of provisioning (if corresponding fields are marked as visible in request in corresponding template).

### Fixes
- Disabled possibility to edit fields of requests that has status submitted, created with errors or creation failed. 
- Fixed showing of "allow add guests" and "register as hub" values in request details that were obtained from corresponding template but not from request data. 
- Fixed showing horizontal scrollbar when not needed in Overview.


# Release notes September 28, 2021

### Fixes
- Added auto updating of external sharing settings values in SharePoint settings section of templates based on tenant-wide external sharing policy so that corresponding template value can't be more permissive than corresponding tenant-wide value.
- Added close icon to edit channel form in channel settings of team type template settings.
- Fixed showing of no data in requester field of some requests in requests overview.
- Improved adding external users process in user access page so that user doesn't need to wait until whole process is finished.
- Fixed some typos.

# Release notes September 24, 2021

### Fixes
- Fixed user search field in user access onboarding page that just showed loading and couldn't find any user. 


# Release notes September 22, 2021

### Fixes
- Changed site address and team/group mailNickname validation process (concerns New request form) so that whole process is more correct and app performance is improved. 

### Overview & Control Admins
- User access page - all fields in add external user form are mandatory now.


# Release notes September 14, 2021

### Overview & Control End users, Owners and Approvers
- It was added info message to New request page. Message is shown only if there is no templates available for user and indicates that user should contact administrator in order to be able to use templates for provisioning. 
- Details page for teams was extended with uninstall teams app functionality. 


# Release notes September 10, 2021

### Fixes
- Import job - fixed get SharePoint sites functionality that returned not all sites before. 
- Fixed change filter in request overview bug that resulted in empty page when changing filter value before requests have been loaded. 


# Release notes September 9, 2021


### Overview & Control Admins
- It was added functionality that allows admin users to force approve requests. It applies to requests where admin user is not among approvers and requests where admin user is one of several approvers but all approvers are required to approve request. In these cases admin user can force approve request despite request approvers settings.

### Fixes
- Fixed size of description that is shown in the upper section of details page (applies to too long description or description that contains several line breaks). 
- Fixed showing New request page for usual users. It was shown empty page when opening New request page if Visibility settings of one of active templates was on but empty.
- Fixed approve and delete old requests bugs (requests that existed before implementation of Communication site provisioning functionality).
- Removed unnecessary info about assigning of sensitivity labels that appeared after request rejection.

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