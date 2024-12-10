<!DOCTYPE html>
<html>
<head>
  <title>Random Video Redirect</title>
  <script>
    // Add your direct video links here
    const videos = [
      "https://drive.google.com/file/d/17bCnZtuwqqv_2kj69arjJgN4g9i5UHyj/view?usp=drive_link",
      "https://drive.google.com/file/d/1-lYX9GSjgNrVqzeOeKGm_RJGUt3uXKNR/view?usp=drive_link",
      "https://drive.google.com/file/d/1vBi4Qzu4yz68LCMcoUkxD4ZagGhHhA-h/view?usp=drive_link"
    ];

    // Pick a random video
    const randomVideo = videos[Math.floor(Math.random() * videos.length)];

    // Redirect to the selected video
    window.location.href = randomVideo;
  </script>
</head>
<body>
  <p>Redirecting to a random video...</p>
</body>
</html>
