# UI: KANBAN
UI workflows for "Kanban". Adobe XD Assets for Antera Application Development UI Kit



## Isolated Kanban Card Component
The kanban card represents a single item (product). It allows the user to see a quick view of the most important information about that item.

A kanban card has the ability to:
1. Be set as a priority which means that it goes to the top of the list within that swim lane.
1. Manage tags for this specific item. Tags are essentially filters that display on the card. When clicked they filter the field of items within the swim  lane
1. Clone this item. Make a direct copy in the same swim lane
1. To be dragged and dropped along the x-axis (ie>[]) ** optional



## Isolated Swim Lane Component
The swim lane in the kanban view represents a stage in the process of the parent module. In this example this swimlane represents all the items in the "Invoiced" stage of the "Production" process.

A single swim lane has the ability to:
1. Display the title of the swim lane
1. Display the total value of all items in the swim lane (ie. all the items invoiced.)
1. Select all kanban cards in the swimlane.
1. Bulk delete
1. Bulk tag
1. Bulk clone
1. Delete the swim lane
1. Maintain a sticky header.
1. Lazy load 20 more items when the user scrolls to the bottom


## Isolated Swimlane Container Component
The swim lane container is the component that visually holds all swim lanes in the kanban view.

The swim lane container has the ability to:
1. Add new swim lanes
1. Name the swim lane
1. Define what the lane is totaling?
1. Drag & drop swim lanes locked along the y-axis
1. Scroll horizontally to see more swim lanes

## Header Grid Filter
The header is a grid of filters at the top of the UI. The header grid filter uses the grid list ("mat-grid-list") component from Angular Material. Each column of the grid contains a different filtering component to filter the data set.

For the kanban card view the header grid filter has the ability to:
1. Display the title of the module/page.
1. Use the search input field to search against a specific scope within the data set.
1. Filter the data set by predefined due dates
1. Add an item to the data.
1. Navigate to the list view
1. Display other settings when you click the gear icon
1. Show the advanced filters slide out tabes module.
1. Show the saved searches tab of the advanced filters tab component

Features

Search (filter) the items displaying by typing in search bar

Change the scope of the search

Show the advanced search menu

Filter items by the due date

Show menu of advanced features

Interface

Module Title

Header: Scoped Filter, Kanban View, List View
A module has a list view and a kanban view. This header allows the user to:




## HOW ...?
1. How do you edit a
1. How do you add cards to a swim lane?
1. How do you edit a single swim lane?
1. How do you determine what it is totaling?



## WHAT IS MISSING?
1. Tag SINGLE kanban card management dialog UI
1. Clone SINGLE kanban card dialog UI
1. Delete SINGLE kanban card dialog UI
1. Tag BULK kanban card management dialog UI
1. Clone BULK kanban card dialog UI
1. Delete BULK kanban card dialog UI
1. Adding a swim lane (name/define total)
1. Add Item to data set (Add Product)
1. Saved Search UI
1. Saved search dialog UI
