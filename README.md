# Zhongyi Jin personal website

This is a two-page static website. It does not require Ruby, Jekyll, or a build step.

## Preview locally

From this directory, run:

```bash
python3 -m http.server 8080
```

Open `http://localhost:8080`.

## Publish on GitHub Pages

1. Upload these files to the root of the `main` branch of your GitHub repository.
2. In the repository, open **Settings**, then **Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Choose the `main` branch and `/(root)`, then save.

GitHub will serve the page automatically after each commit.
