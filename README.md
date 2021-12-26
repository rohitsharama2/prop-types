# prop-types
Defining a Simple List using Prop - types library



Link to repo https://codesandbox.io/s/laughing-cdn-o4lre?file=/src/index.js


Questions Asked 
1.Explain what the simple List component does.
2.What problems / warnings are there with code?
3.Please fix, optimize, and/or modify the component as much as you think is necessary.


1 .The List Component takes an Array of objects and displays a list containing names and the background Color changes according to selected item , it changes to green for the selected item and remains red for unselected.

2. Problems /warnings 
  In WrappedSingleListItem while displaying the background color selected item was not equated with current index so bg color was not changing
  In WrappedListComponent the Hooks were defined wrong , it should be interchanged
  In WrappedListComponent prototypes shape were defined incorrectly
  In WrappedListComponent items were defined null which is wrong it should be an array of object
  
3. Fixed the codes whereever Required . 


 !! Will be happy for suggestions.
