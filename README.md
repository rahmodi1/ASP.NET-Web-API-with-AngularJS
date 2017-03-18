# ASP.NET-Web-API-with-AngularJS
Build Single Page Applications using Web API and AngularJS

<h2>Frameworks - Libraries</h2>
<ul style="list-style-type:disc">
  <li>ASP.NET Web API</li>
  <li>Entity Framework</li>
  <li>Automapper</li>
  <li>FluentValidation</li>
  <li>AngularJS</li>
  <li>Bootstrap 3</li>
  <li>3rd part libraries</li>
</ul>  

<h2>Installation instructions</h2>
<ol>
  <li>Build solution to restore packages</li>
  <li>Rebuild solution</li>
  <li>Change the connection strings inside the HomeCinema.Data/App.config and HomeCinema.Web/Web.config accoarding to your development environment</li>
  <li>Open Package Manager Console</li>
  <li>Select HomeCinema.Data as Default project (in package manager console) and run the following commands
    <ol>
      <li>add-migration "initial"</li>
      <li>update-database -verbose</li>
    </ol>
  </li>
  <li>Run HomeCinema.Web application</li>
  <li>Use username: <b>rahul</b>, password: <b>homecinema</b> to login or register a new account</li>
</ol>  
 
<h2>License</h2>

Code released under the <b>MIT license</b>.
