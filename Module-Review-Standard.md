# Module Review Standard

## Application Project

* TodoAppService should implement ITodoAppService.

## Application.Contracts Project

* ITodoAppService interface should contains all the public methods.

## Web Project

* In Pages folder, the Todo folders should in the TodoManagement (module name) folder.
* List pages should have the `Title`, `BreadCrumb` and `MenuItemName` configurations in PageLayout.Content.
* List pages should have actions permission check.
* Localizations of Modal pages should work.
* Sub list pages should show the parent entity identification. For example, using `PageLayout.Content.Title = "TodoItem (TodoName1)";` and `<abp-card-title>TodoItem (TodoName1)</abp-card-title>`
```