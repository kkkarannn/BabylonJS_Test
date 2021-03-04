# AgoraBabylonJS
Test Project by Karan Mistry for Zohaib at Eventgarde

----------------------------------------------------------------------------
Integrations and changes /////////////////////////////////
- Integrated Agora SDK with AppID - 8230a2f9fb5e4e5c8aae14f1af415456
- Added a video background with URL
- Added a ArcCamera with Onclick to set the Video Plane as Target (Tried to do a PointerDragBehaviour but for rotation of the plane but din't work. Babylon is missing this feature, When dragged the videoplane should rotate and not the camera move around. This would be the perfect solution you were looking for, but I have done some workaround)
- Made changes to the code to move Video Planes to the multiple of the StreamCount. So that all the streams appear and not overlap on each other.
----------------------------------------------------------------------------
How to Upload it to Server
- No Need to Compile/Build.
- Move this directory to the public server via FTP/SFTP/FTPS.
- Same with AWS S3 https://aws.amazon.com/aws-transfer-family/?whats-new-cards.sort-by=item.additionalFields.postDateTime&whats-new-cards.sort-order=desc.
- Make sure index.html is in the root folder.
- https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Upload_files_to_a_web_server Follow link for more info.
----------------------------------------------------------------------------
Test on Localhost
- Open the Folder in VSCode.
- Install Extension LiveServer. https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer
- Click GoLive on bottom-right
- The Site will open up in your default browser. Enjoy.
----------------------------------------------------------------------------
