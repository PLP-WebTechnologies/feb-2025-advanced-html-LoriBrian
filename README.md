<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Football Hub</title>
</head>
<body>

    <header>
        <h1>Football Fanatics</h1>
    </header>

    <main>
        <section>
            <h2>About Football</h2>
            <p>Football, also known as soccer, is a team sport played between two teams of eleven players with a spherical ball. It is played by approximately 250 million players in over 200 countries and dependencies, making it the world's most popular sport. The game is played on a rectangular field called a pitch with a goal at each end. The objective of the game is to score by moving the ball beyond the goal line into the opposing goal.</p>
            <img src="https://images.pexels.com/photos/1467926/pexels-photo-1467926.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="Football players in action" width="500">
        </section>

        <section>
            <h2>Major Football Leagues</h2>
            <ol type="1">
                <li>Premier League (England)</li>
                <li>La Liga (Spain)</li>
                <li>Serie A (Italy)</li>
                <li>Bundesliga (Germany)</li>
                <li>Ligue 1 (France)</li>
            </ol>
        </section>

        <section>
            <h2>Top Football Clubs Contact Information</h2>
            <table>
                <thead>
                    <tr>
                        <th>Club Name</th>
                        <th>Stadium Address</th>
                        <th>Contact Number</th>
                        <th>Official Email</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Arsenal</td>
                        <td>Emirates Stadium, London</td>
                        <td>+44 20 7619 5000</td>
                        <td>contact@arsenal.co.uk</td>
                    </tr>
                    <tr>
                        <td>Real Madrid</td>
                        <td>Santiago Bernabéu, Madrid</td>
                        <td>+34 91 398 4300</td>
                        <td>atencioncliente@realmadrid.es</td>
                    </tr>
                    <tr>
                        <td>AC Milan</td>
                        <td>San Siro, Milan</td>
                        <td>+39 02 4879 8400</td>
                        <td>info@acmilan.com</td>
                    </tr>
                    <tr>
                        <td>Bayern Munich</td>
                        <td>Allianz Arena, Munich</td>
                        <td>+49 89 699 310</td>
                        <td>service@fcbayern.com</td>
                    </tr>
                    <tr>
                        <td>Paris Saint-Germain</td>
                        <td>Parc des Princes, Paris</td>
                        <td>+33 1 47 43 71 71</td>
                        <td>contact@psg.fr</td>
                    </tr>
                </tbody>
            </table>
        </section>

        <section>
            <h2>Football Fan Registration</h2>
            <form action="#" method="post">
                <fieldset>
                    <legend>Fan Details</legend>

                    <label for="fanName">Fan Name:</label><br>
                    <input type="text" id="fanName" name="fanName" placeholder="Enter your name" required><br><br>

                    <label for="email">Email:</label><br>
                    <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>

                    <label for="favoriteTeam">Favorite Team:</label><br>
                    <select id="favoriteTeam" name="favoriteTeam">
                        <option value="arsenal">Arsenal</option>
                        <option value="realmadrid">Real Madrid</option>
                        <option value="acmilan">AC Milan</option>
                        <option value="bayern">Bayern Munich</option>
                        <option value="psg">Paris Saint-Germain</option>
                        <option value="other">Other</option>
                    </select><br><br>

                    <p>Interested in League News:</p>
                    <input type="radio" id="yesNews" name="leagueNews" value="yes">
                    <label for="yesNews">Yes</label><br>
                    <input type="radio" id="noNews" name="leagueNews" value="no">
                    <label for="noNews">No</label><br><br>

                    <p>Preferred League Updates:</p>
                    <input type="checkbox" id="premierLeague" name="leagueUpdates" value="premierLeague">
                    <label for="premierLeague">Premier League</label><br>
                    <input type="checkbox" id="laLiga" name="leagueUpdates" value="laLiga">
                    <label for="laLiga">La Liga</label><br>
                    <input type="checkbox" id="serieA" name="leagueUpdates" value="serieA">
                    <label for="serieA">Serie A</label><br>
                    <input type="checkbox" id="bundesliga" name="leagueUpdates" value="bundesliga">
                    <label for="bundesliga">Bundesliga</label><br>
                    <input type="checkbox" id="ligue1" name="leagueUpdates" value="ligue1">
                    <label for="ligue1">Ligue 1</label><br><br>

                    <input type="submit" value="Register">
                </fieldset>
            </form>
        </section>

        <section>
            <h2>Football Highlight Video</h2>
            <video width="640" height="360" controls>
                <source src="your_football_highlight.mp4" type="video/mp4">
                Your browser does not support the video element.
            </video>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Football Hub</p>
    </footer>

</body>
</html>
