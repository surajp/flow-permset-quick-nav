# Edit Permission Sets quickly using Flows

This is a simple screen Flow that lets users select a permset and (optionally) and object to navigate quickly to edit the object's permissions. It also contains quick links for App Permissions, System Permissions and a few other pages for the permset. It also contains a Global Action that uses the Flow through an Aura component. Admins can add this action to their Publisher Layouts to access the Flow from anywhere in the org.

It is recommended to restrict the Flow permissions to System Admins only.

### Installation Links

This is a no-namespace unlocked package, so you may install and edit this in your org.

- [Production](https://login.salesforce.com/packaging/installPackage.apexp?p0=04t6S000001IQstQAG)
- [Sandbox](https://test.salesforce.com/packaging/installPackage.apexp?p0=04t6S000001IQstQAG)

### Note

1. You may see some objects that are not permissionable. When this happens, the Flow will open the overall Object Settings page instead of the specific object permissions page. I couldn't find a good way to filter these out.
2. You may face issues if you a very large number of permission sets or custom objects, especially in managed packages. Considering tweaking the Flow to remove managed package objects if this happens.
