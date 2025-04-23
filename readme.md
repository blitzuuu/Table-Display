## A Dynamic MKW Tablebot Table Display for OBS
To To use this display, insert an MKW Tablebot table ID at the end of this url, replace the "TABLE-ID" text: https://blitzuuu.github.io/Table-Display/index?tableid=TABLE_ID

If you would like your team highlighted add &YOUR_LOUNGE_NAME to the end of the url.
For example, a url using my name would look something like this https://blitzuuu.github.io/Table-Display/index?tableid=1364434792455868426&name=blitzu

Add this link as a browser source in OBS to display the scores, they update as the table is updated with no need to refresh.

If you would like to change the text colour from black to white add "&white" to the end of the url, if you would like to alter the styling further these are the following relevant css elements:

`#table-stats` affects the colour and styling of the race number and dividers
`.team-normal` affects the colour and styling of all teams apart from the player's team (if the url has a name)
`.team-highlight` affects the colour and styling of the player's team (if the url has a name)

## Config Page
If you would like an OBS dock which can update the table ID without having to edit the link you can use the config page. This page requires a lounge name in the url as such: https://blitzuuu.github.io/Table-Display/config?name=YOUR_LOUNGE_NAME

Add this as a custom browser dock in OBS, and then add the index url with no table ID (e.g., https://blitzuuu.github.io/Table-Display/index?YOUR_LOUNGE_NAME). Make sure the name in both urls is the same. Now you can just insert a table ID and click the update button and it will update the link to display the table, to wipe it clear just click the reset button.

### Output
This is what the output looks like (*Note: I also have a semi-transparent black colour source behind my text in OBS to make it more readable*)

![Example Image](images/example.png)

As well as the OBS dock

![Config Image](images/config.png)
