# dotnet.webapi.TodoApi
modified TEMPLATE / EXAMPLE FROM https://docs.microsoft.com/en-us/aspnet/core/tutorials/first-web-api
played with Controllers
  added TodoItemDTOesController and TodoItemDtosController, in addition to existing TodoItemsController
    https://localhost:5001/api/todoitems
    https://localhost:5001/api/todoitemDtos
    https://localhost:5001/api/todoitemDTOes
    https://localhost:5001/weatherforecast
added swagger via nuget pkg manager / nuget CLI
  slightly modified ConfigureServices method in startup.cs
  slightly modified Configure method in startup.cs
    ACCORDING TO FOLLOWING ARTICLE
      https://www.codeproject.com/Articles/5277774/How-to-Create-API-in-NET-Core
        https://localhost:5001/swagger/index.html
