## Changes

* Added requirements.txt
* Using `**data` instead of passing manually in the resources.
* Using list comprehension instead of `list(map())` in the `ItemList` and `StoreList` resources.
* Added more info to `.json()` methods in `ItemModel` and `StoreModel`.
* Modified `ItemListResource` to use `ItemModel.find_all()` instead of using the `query`—as that encapsulates the database interaction in the model instead of exposing it to the resource.
* Modified `StoreListResource` to use `StoreList.find_all()` as well.