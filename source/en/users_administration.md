---
toc: "users"
maxHeadingLevel: 3
minHeadingLevel: 2
aliases:
  - "users"
  - "users_user_types"
  - "users_library_quota" 
  - "users_dashboards"
excerpt: "Manage Users of the CMS"
keywords: "ownership, user types, super admin, group admin, onboarding wizard, home folder, adding users, reset two factor authentication, force password change, library quota, dashboards, homepage"
---

# User Management

[[PRODUCTNAME]] has different User types, each allowing a varying level of access across the CMS for efficient collaboration.

Administrators are encouraged to assign **Users** to **User Groups** to determine what the Users should access within the CMS and share **Folders** with the User to control the interaction (View, Edit, Delete)  of items contained within the Folder. 

{nonwhite}

## How-to Video Creating Users

{video}3CKS7BBV0fk|how_to_creating_users_5.png{/video}
{/nonwhite}

## Creating Users

Users are created and managed by clicking **Users** under the **Administration** section of the  main CMS menu.

- To add new Users, click on the **Add User** button

- Use the drop down to select the User Type

A **User** will only have access to the parts of the CMS assigned to the User Group they belong to as well as full editing rights to their own items and the ability to share those with other Users.

Some Users may need additional access rights in order to perform the correct tasks, such as a **Group Admin**, who in addition to having access to the parts of the CMS as assigned to the User Group they belong to, they will also get access to all items of all Users belonging to the User Group.

- Select from one of the pre-configured User Groups

These groups already have appropriate Features set so that common functions match the described role or create your own User Groups which would could then be selected from here.

Users are also assigned a dashboard which serves as a **Homepage**:

- The **Status Dashboard** is a high level view for **Super Admin Users** which shows information relating to Library and Bandwidth usage as well as Display Activity.
- The **Icon Dashboard** is the default **User** view and is intended as a launcher into other areas of the CMS.
- The **Media Manager Dashboard** gives an overview of the status of Library Media in the CMS.
- The **Playlist Dashboard** is only assigned to the **Playlist Dashboard User Group** which gives a restricted view of the CMS with a User only able to select specific Playlists to manage.

To make changes to a Users default homepage, use the row menu and select **Edit**, use the drop down menu for **Homepage**.

- Create a User Name and Password to share with the User for login credentials.
- Select Folders which need to be shared with the User so that they can have access items they need to fulfil their role from the start. Set a default folder to act as a Home Folder for the User.

## Deleting Users

Deleting a User is irreversible and will remove all their owned items including; Media, Layouts and Schedules, even if these items are being used by other Users in the system. **Reassign items** to another User to make them the new owner of all the items currently owned by the User you wish to delete. Alternatively, use the **Retired** checkbox at the bottom of the **Edit User** form so that the items remain in use in the CMS. 

{nonwhite}
{cloud}
Please ensure that the default user account named `xibo_admin` is not modified or removed so that our helpdesk agents can assist you with your CMS as and when required.
{/cloud}
{/nonwhite}

{white}
{cloud}
Please ensure that the default user account named `cms_admin` is not modified or removed so that you can be assisted you with your CMS as and when required.
{/cloud}
{/white}

## Further Reading

[Managing Folders](/configure_folders.html)

## FAQs

***Is there a way to ensure Users change their password within the system?***

Edit a User from the row menu and select the Options tab to find the setting "Force Password Change." Users will be redirected to a page to reset their password, the next time they log in.

***I have a user who has lost access to their Google Authenticator app and has no access to email or any saved recovery codes?***

Edit the User from the row menu and use the checkbox to Reset Two Factor Authentication. The User can now set up two factor authentication from their User Profile.

***How can I add a User to a User Group?***

Use the row menu and select User Groups to manage group membership.

