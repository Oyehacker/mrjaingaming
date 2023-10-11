<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mr. Jain Gaming</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Inside the <header> section in the HTML -->
<header>
    <div class="IMAGES/img.1">Mr. Jain Gaming</div>
        <<!-- Inside the <nav> section in the HTML -->
<nav>
    <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#top-videos" onclick="window.open('https://youtu.be/4K1OwO2qk_s?si=eYSrHvnmeTkaaV0g')">Top Videos</a></li>
        <li><a href="#short-videos" onclick="window.open('https://youtube.com/shorts/MVZ4R59wS2Q?si=MgL_sVEnTrGWTKRX')">Short Videos</a></li>
        <li><a href="#top-games">Top Games</a></li>
    </ul>
</nav>
</header>

    <header>
        <h1>Welcome to Mr. Jain Gaming!</h1>
        <p>Level up your gaming experience with Mr. Jain's adventures!</p>
    </header>
    

    <section class="about">
        <h2>About Mr. Jain</h2>
        <p>Meet Mr. Jain, your gaming companion on this thrilling journey. With a passion for gaming and a knack for entertainment, get ready for a rollercoaster of fun!</p>
    </section>
    <!-- Add this description wherever you want it on your page, for example, below the "Top Videos" section -->

<section class="channel-description">
    <h2>Passionate Gaming Adventures Await!</h2>
    <p>Welcome to the heart of gaming euphoria – Mr. Jain's Gaming World! 🎮 Join me on an exhilarating journey through the pixels and polygons as we explore the vast realm of video games.</p>

    <p>Here, gaming is not just a hobby; it's a passion that pulses through every gameplay, every challenge, and every victory. Prepare for a rollercoaster of emotions – from laughter-inducing escapades to heart-stopping moments of triumph.</p>

    <p>What sets us apart? It's not just about the games; it's about the community we're building. A family of gamers who share the same fervor for immersive experiences and endless fun. Join us, hit that subscribe button, and become a part of the gaming legacy!</p>

    <p>Whether you're a seasoned gamer or just stepping into the pixelated universe, there's a place for you here. Let's embark on this gaming odyssey together – where passion meets pixels!</p>
</section>

    <!-- Add the provided YouTube videos section -->
<section class="youtube-videos">
    <h2>Latest YouTube Videos</h2>
    <div class="video-container">
        <img src="Screenshot (328).png" alt="https://youtu.be/4K1OwO2qk_s?si=eYSrHvnmeTkaaV0g">
        <img src="Screenshot (149).png" alt="https://youtu.be/q7eDXqx9Ick?si=wcjCfwxiCApAypNE">
        <img src="Screenshot (98).png" alt="https://youtu.be/AQ7MoceVW5k?si=yoKH5fgultULOadU">
    </div>
    <a href="#" id="openTopVideos">Open Top 5 Videos</a>
    
</section>




    <section class="impressive-lines">
        <h2>Impressive Lines</h2>
        <p>"Where pixels meet passion, Mr. Jain Gaming is born. Join us in the realm of endless excitement and epic adventures."</p>
        <p>"Gaming is not just a hobby; it's a way of life. Mr. Jain Gaming, where every click unlocks a new world of possibilities."</p>
    </section>

   <!-- Inside the .subscribe section in the HTML -->
<section class="subscribe">
    <h2>Subscribe Now!</h2>
    <p>Don't miss out on the action. Hit that subscribe button to join Mr. Jain on his gaming escapades. Prepare for laughs, challenges, and some jaw-dropping moments!</p>
    <button onclick="window.open('https://youtube.com/@mrjaingaming?si=fkmIwfrXEui0tgmG')">Subscribe Now</button>
</section>

    <footer>
        <p>&copy; 2023 Mr. Jain Gaming | All Rights Reserved</p>
    </footer>
    
<!-- Add the JavaScript just before the closing </body> tag -->
<script>
    document.addEventListener("DOMContentLoaded", function () {
        const topVideosLink = document.getElementById('openTopVideos');

        topVideosLink.addEventListener("click", function (event) {
            event.preventDefault();
            const topVideos = [
                "https://youtu.be/4K1OwO2qk_s?si=eYSrHvnmeTkaaV0g",
                "https://youtu.be/q7eDXqx9Ick?si=wcjCfwxiCApAypNE",
                "https://youtu.be/AQ7MoceVW5k?si=yoKH5fgultULOadU",
                "https://youtu.be/zT4pKVcZNzc?si=n3bMhhXnZ0vqaea8",
                "https://www.youtube.com/watch?v=your_video_id_5"
            ];

            const newWindow = window.open('');
            topVideos.forEach(videoLink => {
                newWindow.document.write(`<p><a href="${videoLink}" target="_blank">${videoLink}</a></p>`);
            });
        });
    });
</script>


</body>
</html>
