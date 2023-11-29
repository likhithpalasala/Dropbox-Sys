This project is a photo-album application that interacts with Dropbox to upload, display, and delete images. The application is built in PHP and utilizes the Dropbox API for file operations.

## Features

1. **Upload New Image:**
   - Use the provided form to upload a new image to your Dropbox images folder.
   - Make a POST request to `album.php?userfile=file.jpg` to initiate the upload.

2. **List and Display Images:**
   - View a list of image names in your Dropbox directory.
   - Each image name is a link that, when clicked, downloads and displays the image in the image section.
   - Make an HTTP GET request to `album.php?display=file.jpg` to view a specific image.

3. **Delete Image:**
   - Each image name has a button to delete it from the Dropbox storage.
   - Make an HTTP GET request to `album.php?delete=file.jpg` to delete a specific image.
