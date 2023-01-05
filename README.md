## Lessons
1. Introduction
2. Install dev tools
3. Create angular app
    1. create project folder
    2. install @angular/cli
    3. create app as frontend
4. Add header
    1. generate component
    2. add html
    3. add css
5. List Foods
    1. create food model
    2. create data.ts
        1. add sample foods
    3. add images to assets
    4. create food sevice
    5. create home component
        1. add ts
        2. add html
        3. add css
6. Search
    1. add method to food service
    2. add search route
    3. show search result in "Home Component"
    4. generate search component
        1. add to home component
        2. add ts
        3. add html
        4. add css
7. Tags Bar
    1. create tag model
    2. add sample tags to data.ts
    3. food service
        1. add get all tags method
        2. add get all foods by tag method
    4. add tags rout
    5. show tag result in "Homw Component"
    6. generate tags component
        1. add to home component
        2. add ts
        3. add html
        4. add css
8. Food Page
    1. add method to food service
    2. generate food page component
        1. add route
        2. add ts
        3. add html
        4. add css
9. Cart Page
    1. creare "Cart Item" model
    2. create "Cart Model"
    3. generatr cart service
    4. add to cart button in food page
    5. generate cart page component
        1. add route
        2. add ts
        3. add html
        4. add css
    6. add dynamic item count to header cart
10. Not found
    1. generate component
        1. add ts
        2. add html
        3. add css
    2. add to pages
        1. home page
        2. food page
        3. cart page
11. Connect To Backend
    1. Create backend folder
    2. npm init
    3. npm install typescript
    4. Create tsconfig.json
    5. reate .gitignore
    6. Copy data.ts to backend/src
    7. npm install express cors
    8. Create server.ts
        1. install @types
        2. add APIs
    9. npm install nodemon ts-node --save-dev
    10. Add urls.ts to frontend
    11. Add HttpClient module
    12. Update food service
Login Page

Generate Component

Add to routes
Add ts
Add html
Import Reactive Forms Module
Add Css
Add Login Api

Use json
Add jsonwebtoken
Test Using Postman
Generate User Service

Generate User model
Add User Subject
Add Login Method
Add User Urls
Generate IUserLogin interface
Add ngx-toastr
Import Module
Import BrowserAnimationsModule
Add styles in angular.json
Add to Header
Add Local Storage methods
Add Logout Method
Add to Header
Make Components For Login Page

Input Container
Input Validation
Text Input
Default Button
Connect Login API To MongoDB Atlas

Moving Apis into routers
Create MongoDB Atlas
Create .env file
Install
mongoose
dotenv
bcryptjs
express-async-handler
Connect to MongoDB Atlas
Use MongoDB instead of data.ts in apis
Register User

Add Register api
Add Register service method
Add Register link
Add Register Component
Loading!

Add Image
Add Component
Add Service
Add Interceptor
Checkout Page

Create Order Model
Create Checkout Page Component
Add To Router
Add User to User Service
Add Cart to Cart Service
Create Order Items List Component
Adding Map To The Checkout Page
Add Leaflet npm package
Add @types/leaflet
Add Css to angular.json
Add AddressLatLng to Order Model
Create Map component
Add to checkout page
Add TS
Change app-map selector to map
Add Html
Add CSS
Add Auth Guard
Save Order
Add Order Model
Add Order Status Enum
Add Auth Middleware
Add Order Router
Add create API
Add Order Urls to urls.ts
Add Order Service
Add create Method
Add Auth Interceptor
Payment Page

Generate Component
Add 'getOrderForCurrentUser' api
Add Order Service method
Connect Component to Service
Make the map component readonly
Adding Paypal

Generate Component
Add to payment page
Get Paypal client Id
Add Paypal JS to index.html
Set up Paypal button
Add Pay api to order router
Get Paypal sandbox account
Order Track Page

Generate Component
Add to routes
Add API
Add to urls.ts
Add method to order.service
Add HTML
Add CSS
Deploy On Heroku

OutputPath in angular.json
package.json
frontend
backend
root
BASE_URL in urls.ts
Public folder config in server.ts
Run commands
Add built folder to .gitignore
Commit and Push
Updating Packages (Optional)

Install npm-check-upates as a global package
Run ncu -u in the frontend folder
Downgrade typescript to version ~4.8.2
Run npm install --force
Run npm start
Run ncu -u in the backend folder
Run npm install
Run npm start