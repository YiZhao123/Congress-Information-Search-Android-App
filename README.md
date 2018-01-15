# Congress-Information-Search-Android-App

The brief summary of the congress search app

The struct of the project is the main activity with four fragments : legislators, bills, committees and favorites. In each fragment, I use the tab layout to separate two or three views such as BY STATES, HOUSE and SENATE. In each view, I used the listview and adapter to show data as the list format.

I used the thread to deal with getting and passing the data to the listview layout. In the onstart method of main activity, I get the data and passing the data to the initialed view.

When I click the row, I will start a new activity to show the detail information. I pass the Jsonobject in String formant into the intent and the new activity get the Jsonobject to show the detail info.

The “about me” is a new activity when you click the item in the navbar.  The favorite data is three arraylists with the JsonObject element, which are the static public variables in the main activity.
