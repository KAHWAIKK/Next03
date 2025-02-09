PRIVATE FOLDERS

In Next.js, private folders are directories that Next.js does not expose to the client. These folders are meant for server-side logic, configurations, and other backend-related files that should not be directly accessible from the browser.****

To create a private folder, add an underscore at the start of the folder name

IMPORTANCE OF PRIVATE FOLDERS

  1. kEEPING YOUR UI LOGIC SEPARATE FROM ROUTING LOGIC
  2. HAVING A CONSISTENT WAY TO ORGANIZE INTERNAL FILES IN YOUR PROJECT
  3. MAKING ITEASIER TO GROUP RELATED FILES IN YOUR CODE EDITOR
  4. AVOID POTENTIAL NAMING CONFLICTS WITH FUTURE NEXTJS FILE NAMING CONVENTIONS

ROUTE GROUPS

lets us logically organize our routes and projects files without impacting the URL structure

Lets build three routes 
    1.regitration
    2.login
    3.forgot password

Instead of having this individual routes you can have one folder to house all related routes e.g Auth

To create a route group you wrap the folder name in parenthesis