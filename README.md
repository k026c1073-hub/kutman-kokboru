# Web Application About Kok-Boru

This project provides information about Kok-Boru, a traditional Kyrgyz horse-riding sport. The web page presents the history and rules of the sport, as well as related images and videos.

## Project Structure

```text
.
├── index.html       # Main web page
├── about.html       # Additional page about the author
├── style.css        # Website styles
├── kut.jpg          # Profile image
├── history.jpg      # History image
├── make.png         # Kok-Boru image
├── place.jpg        # Venue image
└── sake.mp4         # Kok-Boru video
```

## How to Run

When `index.html` is opened directly, the browser may block local videos for security reasons. Therefore, run the project through a local web server.

In PowerShell or the VS Code terminal, run the following command from the project root folder:

```powershell
python -m http.server 8002
```

Then open this address in your browser:

```text
http://localhost:8002/index.html
```

Keep the terminal open while the server is running.

## Videos

Both video elements use the `sake.mp4` file. The video controls are hidden, and the videos play automatically without sound.

## Publishing with GitHub Pages

To allow a teacher to view the website on another computer, upload the project to a GitHub repository and publish it from the repository's `Settings → Pages` section:

1. Select `Deploy from a branch` under `Source`.
2. Select the `main` branch and `/ (root)` as the folder.
3. Click `Save`.
4. Send the website link provided by GitHub to the teacher.

The `http://localhost:8002/...` address works only on your computer. Send the `https://...github.io/...` link provided by GitHub Pages to the teacher.

## Copyright

Images and videos should be created by the project author or used with permission. Do not publish other people's materials without permission.