# GTA 6 Live Countdown Overlay

A premium, highly interactive, and visually stunning live countdown overlay web application designed for YouTube streamers. Perfect for embedding directly into OBS Studio or streaming software as a browser source.

## Features

- **📺 Interactive Stream Dashboard**: Frosted glassmorphism design with real-time countdown timer cards, dynamic neon overlays, and scrolling ticker marquee.
- **⚙️ Editable Admin Panel**: A hidden settings drawer is built right into the webpage. 
  - Double-click the background or press the **`Esc`** key to open the overlay controls.
  - Modify countdown title, logo names, ticker texts, target dates, accent glow colors, background blurs, canvas particle density, and music streams.
- **🖥️ OBS Studio Optimizer**: Includes a "Hide Settings Gear" option (OBS Mode). Hides UI buttons from the stream output while keeping them accessible via keyboard hotkeys (`Esc`) or background double-clicks.
- **✨ Animated Canvas Particles**: Custom canvas particle system rendering floating neon embers that follow your chosen theme colors.
- **🎵 Music Sync**: Support for background loop music with custom volume and autoplay safety checks.
- **💾 Local Storage Persistence**: All customizations and edits are saved directly in your browser's local cache. They reload automatically when the stream restarts.

---

## 🚀 How to Host on GitHub Pages

Hosting this site on GitHub Pages makes it globally accessible for your streaming needs:

1. Create a new repository on GitHub (e.g., `gta6-countdown-overlay`).
2. Upload all files from this folder (`index.html`, `gta 6 bg.png`, `gta 6 2.jpg`, `channels4_profile.jpg`, `poster_full.0az_iud2g3y4j.jpg`, and your `music.mp3` if any) to your repository.
3. In your GitHub repository, navigate to **Settings** > **Pages** (on the left menu).
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Set the branch to **`main`** (or `master`) and directory to **`/ (root)`**, then click **Save**.
6. GitHub will generate a live URL for your site, typically: `https://<your-github-username>.github.io/<your-repo-name>/`.

---

## 📽️ How to Set Up in OBS Studio

1. Open **OBS Studio** and locate the **Sources** dock.
2. Click the **`+`** icon and select **Browser**.
3. Name it (e.g., `GTA 6 Countdown Overlay`).
4. **Configuration Options**:
   - **Using GitHub Pages**: Paste your live GitHub Pages URL into the **URL** box.
   - **Using Local Files**: Check the **Local file** box, click browse, and choose `index.html`.
5. Set the **Width** to `1920` and **Height** to `1080` (or match your stream canvas size).
6. Click **OK**.
7. To customize the content (change target countdown date, color schemes, title, etc.):
   - Right-click the Browser source in OBS and select **Interact**.
   - Press the **`Esc`** key on your keyboard or double-click anywhere on the overlay screen background.
   - Change your settings in the sidebar drawer and click **Save Settings**.
   - Check the **Hide Settings Gear (OBS Mode)** checkbox before saving to hide the gear icon from your stream output.
