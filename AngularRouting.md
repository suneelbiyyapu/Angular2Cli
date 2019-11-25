How Routing works in Angular
-----------------------------------
step 1: set <base href="/"> in **index.html**

step 2: Import the **RouterModule** into the application root module **AppModule**

step 3: Configure the application routes

step 4: Specify where you want the routed component view template to be displayed using the <**router-outlet**> directive.

step 5: Create a navigation menu and tie the configured routes with menu using the **routerLink** directive


Generate Routing Module by Angular CLI (At the time of creating Angular app)
----------------------------------------------------------------------------
ng new RoutingSample --routing
