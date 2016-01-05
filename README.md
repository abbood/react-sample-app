# Purpose
This is a sample project that illustrates the use of the react framework in a very simple setting

# Technical setup
The following is the initial stack that should be used, although you can make some changes to the backend choices (ie use python rather than go, but please explain why in the commit message or in this repo's wiki)

## Clients  
   **Core:** React / React Native  
   **Client Data Model:** Relay (https://facebook.github.io/relay/)  
   **Routing:** React Router Relay (https://github.com/relay-tools/react-router-relay)  
   **Generic CSS:** Material UI (http://www.material-ui.com/) (non-native)- For Admins non-user facing pages  
   **Custom CSS:** Radium (http://stack.formidable.com/radium/) (non-native) - For Branded products or products that need a custom look
## Database API
   **Spec:** GraphQL (http://graphql.org/)  
   **Implementation:** Go GraphQL (https://github.com/graphql-go/graphql) Go Relay (https://github.com/graphql-go/relay)  
## Backend:
   **API Server / Static Assets:** App Engine  
   **Datastorage:** Google Cloud Datastore (https://cloud.google.com/appengine/docs/go/datastore/)  
   **Custom:** Things like video processing Managed VMS (https://cloud.google.com/appengine/docs/managed-vms/) - You can use docker here to describe your builds

# Requirements
This application must be a very simple responsive app.. but that said it will have two different designs for the desktop version and the mobile version (in order to test how this framework handles that.. ie is through css or some router or..?)



