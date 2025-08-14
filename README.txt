Habaytta Map — GitHub Pages (JSON data)

Files:
- index.html — the app
- projects.json — your project list (edit this file to add/remove projects)
- assets/projects/placeholder.jpg — placeholder image

How to publish on GitHub Pages:
1) Create a new GitHub repository (e.g., habaytta-map).
2) Upload the *contents* of this folder (index.html + projects.json + assets/).
3) Go to repo Settings → Pages → Build and deployment:
   - Source: Deploy from a branch
   - Branch: main, Folder: / (root), Save
4) Your site will be live at: https://<your-username>.github.io/<repo-name>/

How to add a new project:
- Edit projects.json (directly in GitHub or locally)
- Add a new object like:
  {
    "id": "telaviv-sun-tower",
    "cityId": "tel-aviv",
    "city": "Tel Aviv",
    "area": "Neve Tzedek",
    "name": "Sun Tower",
    "price": "50K-65K NIS",
    "developer": "Example Dev",
    "image": "assets/projects/suntower.jpg",
    "lat": 32.062,
    "lng": 34.767
  }
- Save (Commit changes). The site updates automatically within ~1 minute.
