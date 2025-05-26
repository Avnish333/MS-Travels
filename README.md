# MS-Travels

A travel website project.

## Viewing Locally

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/Avnish333/MS-Travels.git
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd MS-Travels
    ```
3.  **Open the main HTML file:**
    Open the `home.html` file in your web browser to view the website. If you are preparing for GitHub Pages deployment, you should rename `home.html` to `index.html` first.

## Deploying to GitHub Pages

To deploy this website to GitHub Pages, follow these steps:

1.  **Ensure you have an `index.html` file:**
    GitHub Pages requires an `index.html` file in the root of your repository to serve as the entry point for your site. This project uses `home.html` as its main page. You **must** rename `home.html` to `index.html`:
    ```bash
    git mv home.html index.html
    git commit -m "Rename home.html to index.html for GitHub Pages"
    git push
    ```

2.  **Enable GitHub Pages in Repository Settings:**
    *   Navigate to your repository on GitHub (`https://github.com/Avnish333/MS-Travels`).
    *   Click on the **Settings** tab.
    *   In the left sidebar, click on **Pages**.
    *   Under "Build and deployment", for the **Source**, select **Deploy from a branch**.
    *   Under "Branch", select the `main` branch (or your default branch) and the `/root` folder.
    *   Click **Save**.

3.  **Access your site:**
    After a few moments, your site should be published at `https://<your-username>.github.io/MS-Travels/` (replace `<your-username>` with your GitHub username). You might need to wait a few minutes for the deployment to complete.
