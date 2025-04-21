# IanPlay
README for IanPlay Music Platform



 Project Overvie
IanPlay is a web-based music platform that allows users to explore, play, and interact with music. The platform provides features such as trending songs, playlists, liked songs, and albums. It is designed to deliver a seamless user experience with a responsive interface and dynamic functionality.



 Features
1. Trending Songs:
   - Displays the most played songs.
   - Includes details such as the song title, artist, genre, plays, and date posted.
   - Users can play songs directly from this page.

2. Playlists:
   - Users can create, view, and delete playlists.
   - Songs can be added or removed from playlists.

3. Liked Songs:
   - Displays songs liked by the user.
   - Users can play or unlike songs.

4. Albums:
   - Displays albums posted by artists.
   - Includes a search feature to find specific albums.

5. Music Player:
   - Custom audio player with play/pause, seek, and volume controls.
   - Persistent playback state to ensure music continues playing even during page interactions.

6. Comments:
   - Users can post comments on songs.
   - Comments are displayed dynamically without refreshing the page.



 Technologies Used
- Frontend:
  - HTML5, CSS3, Bootstrap
  - JavaScript (with AJAX for dynamic updates)
- Backend:
  - PHP (with MySQLi for database interactions)
- Database:
  - MariaDB (MySQL)
- Other Tools:
  - Font Awesome (for icons)



Database Structure
- Users Table:
  - Stores user information such as username, email, and role.
- Music Table:
  - Stores song details such as title, genre, artist, and file path.
- Playlists Table:
  - Stores user-created playlists.
- Playlist Songs Table:
  - Links songs to playlists.
- Likes Table:
  - Tracks songs liked by users.
- Comments Table:
  - Stores comments on songs.



Installation Instructions
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/your-repo/ianplay.git
   ```
2. Set up the database:
   - Import the `music_platform.sql` file into your MySQL/MariaDB database.
   - Update the database credentials in database.php.

3. Start the server:
   - Use XAMPP or any PHP server to host the project.
   - Place the project folder in the `htdocs` directory (if using XAMPP).

4. Access the platform:
   - Open your browser and navigate to `http://localhost/IanPlay`.



Usage
1. Login/Register:
   - Users must log in or register to access the platform.
2. Explore Music:
   - Navigate to "Trending Songs" to explore popular tracks.
3. Create Playlists:
   - Go to "Playlists" to create and manage your playlists.
4. Like Songs:
   - Click the "Like" button on the music player to save songs to your liked list.
5. Search Albums:
   - Use the search bar on the "Albums" page to find specific albums.


File Structure
- Frontend:
  - index.html: Landing page.
  - trending_songs.php: Displays trending songs.
  - `playlists.php`: Manages user playlists.
  - `liked_songs.php`: Displays liked songs.
  - `albums.php`: Displays and searches albums.
  - `music_player.php`: Custom music player.
- Backend:
  - add_comment.php: Handles adding comments.
  - like_song.php: Handles liking/unliking songs.
  - delete_playlist.php: Handles playlist deletion.
- Database:
  - `music_platform.sql`: Database schema and sample data.



 Future Enhancements
- Add a recommendation system for personalized song suggestions.
- Implement user profiles with activity tracking.
- Add support for uploading songs and albums by artists.



 Contributors
- Ian Tchikalema (Project Lead)



 License
This project is licensed under the MIT License.
