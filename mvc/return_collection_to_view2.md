**Returning a Collection from Controller to View**

To return a collection of objects to a view from a Controller, just pass in the View statement the collection that you want pass.

**Example**

_Controller_

```
  public ActionResult Users()
  {
      List<WebUsers> web_users = WebManager.GetWebUsers()     
      return view(web_users);     
  }
```

 _Users View_

```
@model IEnumerable<AppNameSpace.Models.DTO.WebUsers>

//To display collection in the User View
 @foreach (var item in Model)
 {
       <li class="list-group-item">
               @item.UserName
               <span class="glyphicon glyphicon-ok" aria-hidden="true"></span>
       </li>
  }


```

 The above example is a very basic example, however, you can have pass class that have many collection properties.

