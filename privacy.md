Sunlit privacy policy
---------------------

This privacy policy describes what personal information the Sunlit app and the sunlit.io web server collect and how that data is used. Riverfold Software LLC owns and maintains the app and web server, but does not control the App.net server or API. All files stored on App.net by Sunlit can be browsed and deleted by other third-party App.net apps.

Sunlit stores the following data on your iPhone:

* App.net username and authentication token to use the App.net API. This is stored securely in the keychain.
* Photos you have explicitly imported into the app, or photos that have synced from other users sharing with you. These are stored in app's Documents folder.
* Thumbnails of photos you have browsed via your camera roll, Photo Stream, or Dropbox.
* Text descriptions you have added to a story. This is stored along with references to the stories and photos in a SQLite database.
* GPS location information for check-ins. This is also stored in SQLite.

The sunlit.io web server collections the following information:

* If you enable push notifications, Sunlit sends your App.net user ID, username, and a special app-specific device token to the server. This is used to notify users of certain activity, such as when someone subscribes to a story you have shared with them.
* If you subscribe to someone's story, Sunlit sends that person's App.net user ID to the sunlit.io server so that it can send a push notification to that user.
* If you publish a story to the web, Sunlit uploads your photos and an HTML version of the story as public files on App.net, and sends a copy of the HTML only to sunlit.io. The sunlit.io server does not store any photos, it merely references the public photos on App.net.
* All connections between Sunlit and sunlit.io use SSL. Publishing uses App.net "identity delegation" to verify that the publishing user actually belongs to the correct App.net account.

How Sunlit syncs to App.net:

* When you add a photo to Sunlit, it starts uploading that photo to App.net as a private file. That file can be viewed by other apps that you have allowed to access your App.net account by giving those apps the "files" privilege.
* When publishing to App.net, Sunlit uploads a second copy of the image and marks it as public. It is then viewable by anyone with the direct public URL.
* Story titles, text, and some other metadata is stored in an App.net private channel. When you share a story with another user, you are giving that person read/write access to that story's private channel. Photos and location check-in data are stored as messages in that channel.
* Sync is on by default and cannot currently be disabled.

If you have any questions not answered in this document, please email support@riverfold.com.