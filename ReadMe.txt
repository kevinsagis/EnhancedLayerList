Built with Web App Builder 2.4

Example demo site of widget is posted here: http://sagiscloud.thempc.org/elayerlist/

The Enhanced Layer List widget is located in eLayerList folder of this WAB site. The Enhanced Layer List is updated to WAB 2.4.  The rest of the website merely serves as a demonstration and it is intended for users to copy the eLayerList folder to their own WAB Application folder. The widget and this demo site will be upgraded to WAB 2.3 or newer in the future as well.  

Files that were modified are widgets\eLayerList\PopupMenu.js  and PopupMenuInfo.js

Enhanced Layer List adds metadata Dojo dialogs to display the Description and Copyright text fields from the REST service. 
This replaces the standard out-of-the-box function that opens a new tab or window to display the Esri REST Service page when a user clicks the "Description" item in the '...' menu on a layer in the Layer List widget, and displays these dialogs instead. This is more friendly to the end user.

It only displays Copyright if it's present. Same for Description. It won't display a Dialog if there is no description, such as for Group layer IDs.

Also includes modification to the LayerListView.js file to autoexpand layerlist based on posts from Robert Scheitlin et al in https://geonet.esri.com/thread/160914

by Kevin MacLeod, SAGIS 
www.sagis.org

Disclaimer: All code and instructions provided with no warranty or guarantee of any kind express or implied.

License: MIT / open source. Feel free to copy, contribute, modify and distribute. We are not responsibile for any use, liability or damages with using this code.
