# Project Crud

1. First start by cloning this repository using `git clone git@github.com:kleberson154/node-do-zero.git`.
2. Install the packages with `npm install`.
3. Navigate to the routes.http file.

4. To create a video, make a Send Request (I recommend using VSCode's REST Client extension) in the POST request. To customize the information, simply change the content inside the `{ object.
  "title": "Video 100",
  "description": "this is my video",
  "duration": 300
}`

5. To see what has been created, use the GET route
     option 1 -  With the default link `https://node-do-zero-1doj.onrender.com/videos` you will search for all the links that have already been created.
     option 2 - You can also add `?search={video name}` to the end of this link`https://node-do-zero-1doj.onrender.com/videos` to search for a specific video.

6. With the PUT route you can make a change to either the title, description or duration, to specify the video to be changed just add the unique ID of the video at the end of the link `https://node-do-zero-1doj.onrender.com/videos/{ put the ID here! }`

7. And finally, to delete a video, just use the DELETE route, adding the unique ID to the end of the link `https://node-do-zero-1doj.onrender.com/videos/{ put the ID here! }`

![Screenshot 2024-03-04 150718](https://github.com/kleberson154/node-do-zero/assets/79817657/80e36883-5d96-402b-b945-711676e2d554)
