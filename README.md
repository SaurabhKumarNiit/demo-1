## Sprint 5 : Guard Routes in an SPA

This sprint has 2 demos

[**Demo 1 :: Prevent Unauthenticated Access**](./demo-1/)

###### Problem Statement

The Fruit-Fantasy application allows users to add, view, modify and delete fruit details.

The application should ensure that these views are accessible only to the user with valid vendor code. If an unauthenticated user attempts to navigate to these views, the user should be redirected to the login view.

**Note:** Routes should be guarded in the `Fruit-Fantasy` app. Use the solution code developed in the `Demo 4: Design UI using Angular Material Schematics` of `Sprint 4: Implement Navigation using Angular Routing`

[Click here for solution and implementation steps](./demo-1)

[**Demo 2 :: ​**](./demo-2/)

###### Problem Statement

Enhance the Fruit-Fantasy app to allow user to select a fruit and modify its details.

The details of selected fruit should be displayed in a separate component.

Define route with parameter, where the parameter value is the id of the selected fruit.

The component displaying details of selected fruit should read the id from the route and fetch the details of fruit for this id.

**Note:** To develop the solution for `fruit-fantasy` app , modify the solution code developed in the `Demo 1: Enable Routing in Fruit-Fantasy` of this sprint.

[Click here for solution and implementation steps](./demo-2)

[**Demo 3 :: Configure Wild Card Routes and Route Redirects in Fruit-Fantasy App​**](./demo-3/)

###### Problem Statement

For the invalid route URLs, define route in Fruit-Fantasy app that navigates user to view that shows the error message.

Also, define route in Fruit-Fantasy app, that redirects users to home view of `Fruit-Fantasy` app as soon as the app is launched in browser. (without providing `\home` in the route URL)

**Note:** To develop the solution for `fruit-fantasy` app, modify the solution code developed in the `Demo 2: Create View to Edit Selected Fruit` of this sprint.

[Click here for solution and implementation steps](./demo-3)

[**Demo 4 :: Enable Navigation from Fruit-Detail to Home View​**](./demo-4/)

###### Problem Statement

Update the solution code of `Fruit-Fantasy` app to allow app to navigate back to home view after the user has edited the fruit details in `Fruit-Detail` component.

**Note:** To develop the solution for `fruit-fantasy` app, modify the solution code developed in the `Demo 3: Configure Wild Card Routes and Route Redirects in Fruit-Fantasy App` of this sprint.

[Click here for solution and implementation steps](./demo-4)