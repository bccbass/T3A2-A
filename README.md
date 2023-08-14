## Data Flow Diagrams

The primary ways data flows within the application are standard user registration/login actions, full crud for a collection spaces (larger areas of a property ie. front yard, back yard) and full crud operations for areas (sub-sections of a space ie. northwest flower bed, verge). Both spaces and areas allow for user provided name, description and notes, stored in a the users collection on the database. Additionally the app allows for user uploaded images of spaces and areas which are uploaded to an AWS image server which responds with an image URL. The returned image URL is then stored appropriately in the users collection on the database. 

![data flow overview](./docs/dataflow-diagrams/overview.jpg)
###### Data flow: Overview  
</br>  

![data flow overview](./docs/dataflow-diagrams/full-view.jpg)
###### Data flow: Full View

</br>  

![data flow login](./docs/dataflow-diagrams/login.jpg)
###### Data flow: Login

</br>  

![data flow view spaces/areas](./docs/dataflow-diagrams/view-spaces-areas.jpg)
###### Data flow: View Spaces and Areas

</br>  

![data flow create/update spaces/areas](./docs/dataflow-diagrams/create-update-spaces-areas.jpg)
###### Data flow: Create/Update Spaces and Areas

</br>  

![data flow add images](./docs/dataflow-diagrams/add-images.jpg)
###### Data flow: Add Images



