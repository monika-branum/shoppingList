Demo Link: https://web-shopping-list-supabase.netlify.app/

Rubric:

Shopping Page

[] Successful authentication should redirect to the shopping page
[] Unauthenticated users trying to visit shopping page should be redirected to login
[] Users should see a list of their shopping list items
[] Users should be able to add an item to their shopping list
[] When a user clicks on an item, it should be updated to `bought=true`
[] When an item is bought, it should display differently on the page
[] Users should be able to delete all shopping list items

Functions

[] ASYNC `createItem(item)` -- adds a new item
[] ASYNC `deleteAllItems()` -- deletes all items
[] ASYNC `fetchItems()` -- fetches all item
[] ASYNC `buyItem(id)` -- udpates specific item to `bought=true`
[] PURE `renderItem(item)` -- takes an item object and returns a DOM element
[] IMPURE `displayListItems()` -- fetches the items from supabase, clears out the DOM, rerenders them
