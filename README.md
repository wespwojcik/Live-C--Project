# Live Project-Csharp Asp.Net MVC

<h1>Introduction</h1>
  <p>This was a two week live project at prosper IT Consulting where I worked with a team of developers to build an interactive
    website for a theater company to manage its website content using MVC Crud Technology. This site included multiple areas to manage
    admin, subscriber, and general website needs as well and included information on the current and past productions, cast members, ect.
    
    The project was built using ASP.Net MVC and Entity Framework in C# with Bootstrap styling. 
    We used Visual Studio as the IDE with Azure Devops and Agile/Scrum methodologies to  develop this project.</p>
  
  
  
  
  <h1>Create an Entity Model for Castmembers and CRUD pages.</h1>
  
  For this story I created a model using entity framework and setting up CRUD pages for this model. I used code first workflow using entity framework to make this happen
  I created an enum to establish the role each cast member is apart of. 
  
  ![CastMemberModels](https://user-images.githubusercontent.com/67170488/128782738-d57ad217-1f6e-4b36-a763-db8e9068ed1f.jpg)


  <h1>Image photo and retrievel story.</h1>
  
  For this story I was tasked with allowing the user to add a image to their create and edit page and upload that photo while the controller converts it from Jpg to a byte array. 
 
   <b>Create View</b>
  ![CreateView](https://user-images.githubusercontent.com/67170488/128784057-3ada5a8c-633c-4b8b-9908-97b47b71d86e.jpg)

  <b>Edit View</b>
  ![EditView](https://user-images.githubusercontent.com/67170488/128783290-eae9d6bc-0462-4394-b220-0a874febe165.jpg)

  <b>Edit Controller</b>
  ![EditController](https://user-images.githubusercontent.com/67170488/128783317-73a68c23-db5d-4bfa-8915-4812304134a3.jpg)
  
  <b>Create Controller</b>
  ![CreateController](https://user-images.githubusercontent.com/67170488/128783354-2b11ffca-4300-49c7-900d-4a3735248835.jpg)



  Create Index page with styled Cards story
  
  For this story I was tasked with displaying the contents of my castmembers model on a bootstrap card. In order to achieve this I had to convert my byte array image file back     into a jpg file to properly display the image. I created an asynchronous method which I used to convert the Jpg before I actually rendered it out to a view page.
  
  
  <b>Index Controller</b>
  ![IndexController](https://user-images.githubusercontent.com/67170488/128784371-c6b7c220-7ed1-4e19-a786-68a91d2980ee.jpg)
  
  <b>Index View</b>
  ![Index](https://user-images.githubusercontent.com/67170488/128784547-26cc19f1-2b1b-493f-93f6-4ca871f49472.jpg)


  <b>Index Card UI</b>
  
  ![Card_Final](https://user-images.githubusercontent.com/67170488/128784560-d5aa6dbd-7c77-40df-9051-cd04e9897b2b.jpg)
