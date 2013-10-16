Sunlit for iPhone URL schemes
-----------------------------

**sunlit://subscribe?channel=12345**

> Subscribe to someone else's story given the story's App.net channel ID. The user must have already shared the story and explicitly added you as a collaborator. (This URL is automatically included when notifying someone about a shared story.)

**sunlit://publish?story=My%20Trip**

> Publish one of your existing stories, given a story name. If the story has a space in its name, it should be URL encoded.

**sunlit://open?story=My%20Trip**

> Open one of your existing stories by name.

**sunlit://create?story=Vacation**

> Create a new blank story and give it a name.

**sunlit://addphoto?story=Vacation**

> Add a photo from the clipboard to an existing story. The clipboard can contain one or more images. (Can be used with Launch Center Pro to add photos from other apps.)

**x-callback-url**

> To return to another app after Sunlit processes the request, include an x-callback-url parameter when calling Sunlit, with a value of the other app's URL scheme.
