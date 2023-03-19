**Implement the React App With the Filtering Feature and Implement the Routing,Context API and use Redux for the State Management.**

- **App should contain following Components**

Home Component

Product Component

User Component ContactUs Component Login Component

Product details Component Nav Component

- Whenever Application Starts, It Should Show the Login Component as Following

![](https://ik.imagekit.io/njzqmguob/Aspose.Words.b3d69670-1798-4ac2-be13-6129f0cd38d6.001.png?updatedAt=1679243493277)

- After entering the Credentials and on clicking login button, If Credentials are Valid then User should Navigate to the the Home Page or else show alert msg to user to enter Proper Credentials
- Home Component (page) Should look like the below UI.

![](https://ik.imagekit.io/njzqmguob/Aspose.Words.b3d69670-1798-4ac2-be13-6129f0cd38d6.002.jpeg?updatedAt=1679243493367)

- If User click on Products in Navbar,Then User Should Navigate to the Products Component
- UI Should look in the Following way

![](https://ik.imagekit.io/njzqmguob/Aspose.Words.b3d69670-1798-4ac2-be13-6129f0cd38d6.003.jpeg?updatedAt=1679243493534)

- Here the Links on Left Panel should come from the Following URL

API: <https://fakestoreapi.com/products/categories>

- On the Right Panel, show only the Titles (Title will be received from the API) of Products in the link format.
- By default on the Right Panel, show Electronic Products Title Details and fetch data from the following API.

**API**: <https://fakestoreapi.com/products/category/electronic>.

- On Click of any Link in Left Panel like Jewellery or MensClothing or women's Clothing,
- Fetch the Product Details of Respective Category from the Following APIs.
- Display their product titles on the right Panel as a link

**Electronic Category :** <https://fakestoreapi.com/products/category/electronics>. **Jewellery Category:[https://fakestoreapi.com/products/category/jewelery. ](https://fakestoreapi.com/products/category/jewelery)MensClothing:[https://fakestoreapi.com/products/category/men's clothing ](https://fakestoreapi.com/products/category/men's%20clothing)WomensClothing:[https://fakestoreapi.com/products/category/women's clothing](https://fakestoreapi.com/products/category/women's%20clothing)**

- On Click on any Title Link, User Should Navigate to the Product Details Component And show the details of the Entire Product as following

![](Aspose.Words.b3d69670-1798-4ac2-be13-6129f0cd38d6.004.png)

- In the Product Details Component Display the Entire Details of the Product.
- Details of Specific Product in the Product Details Component Should Come From the Redux Store.
- If User Click on the User Link in the Navbar, then It should look like Following UI

![](https://ik.imagekit.io/njzqmguob/Aspose.Words.b3d69670-1798-4ac2-be13-6129f0cd38d6.004.png?updatedAt=1679243493461)

![](https://ik.imagekit.io/njzqmguob/Aspose.Words.b3d69670-1798-4ac2-be13-6129f0cd38d6.005.png?updatedAt=1679243493296)

- Here in the Users Component, Fetch the Details of User from the following API **API** :[ https://randomuser.me/api/?results=20](https://randomuser.me/api/?results=5000)![](Aspose.Words.b3d69670-1798-4ac2-be13-6129f0cd38d6.007.png)
- Show the Users Details in the Table Format and the User should be able to filter the data Based on the Gender. .
- If User click on Male Radio Button then it Should show only Male Users as Following

![](https://ik.imagekit.io/njzqmguob/Aspose.Words.b3d69670-1798-4ac2-be13-6129f0cd38d6.008.png?updatedAt=1679243493306)

- And If Users Click on female radio buttons show only females.
- If User clicks on the All radio button then shows all the details.
- Implement Filtering Feature using Redux Concept.
- If User Click on contact page then Show the Following UI

![](https://ik.imagekit.io/njzqmguob/Aspose.Words.b3d69670-1798-4ac2-be13-6129f0cd38d6.009.png?updatedAt=1679243493378)

- Add Logout button in the Navbar after the Contact Link
- If User clicks on the Logout Button and then he Should Navigate to the Login Screen.
