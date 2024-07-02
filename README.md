
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Goals</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>My Tech Goals for the Next 2 Years</h1>
        <p>  My goals for the next two years is to Master React with a focus on hooks and performance
            optimization. Gain expertise in state management with Redux, and improve testing skills using Jest and React Testing Library.
            Ensure web accessibility by following WCAG guidelines, and build responsive, user-friendly interfaces.
        </p>
        <div class="profile">
            <h2 data-testid="slackDisplayName">@Ayomi Alakija</h2>
            <p data-testid="slackEmail">ayomialakija3@gmail.com</p>
            <img src="slack profile picture.jpg" alt="Slack Profile Picture" data-testid="slackProfilePicture">
        </div>
        <div class="current-time">
            <p>Current Time (UTC): <span data-testid="currentTimeUTC"></span></p>
            <p>Current Day: <span data-testid="currentDay"></span></p>
        </div>
        <div class="links">
            <a href="https://hng.tech/learn" data-testid="hngLink">HNG Learn</a>
            <a href="https://keyword.dog" data-testid="keywordLink">Keyword Dog</a>
            <a href="https://scrapeanyweb.site" data-testid="scrapeanywebLink">Scrape Any Web</a>
        </div>
    </div>
    <script src="script.js"></script>
</body>
</html>

