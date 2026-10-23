# Code Meets Creator — Personal Portfolio

A personal portfolio website for **Divyanshi RajWansh**, bringing together software development, computer science, and content creation in one place.

The site presents an introduction, skills, project showcase, creator assets, and a contact form in a responsive interface with dark/light theme support.

## ✨ Features

- **Personal introduction** highlighting the connection between technology and creative storytelling
- **About section** with education and skills
- **Project showcase** with search and tag-based filtering
- **Creator Assets page** featuring design boards, video-editing frames, brand concepts, writing/media placeholders, and creator tools
- **Dark/light theme toggle** with the selected theme saved in the browser when storage is available
- **Responsive navigation** for smaller screens
- **Interactive “Chat with Byte” panel**
- **Contact form validation** with an on-page confirmation state
- **Accessibility details**, including semantic page sections, a skip-to-content link, and descriptive image text
- **Vercel configuration** included for deployment

> Some visuals and project information are placeholders. Update them with final assets, real project details, and working social links before presenting the site as a finished portfolio.

## 🧰 Built With

- HTML5
- CSS
- JavaScript
- Google Fonts: Inter and Space Grotesk
- Vercel (deployment configuration included)

## 📁 Project Structure

```text
.
├── index.html
├── assets.html
├── vercel.json
├── .env.example
├── .gitignore
├── css/
│   └── styles.css
├── js/
│   ├── theme.js
│   ├── main.js
│   ├── projects.js
│   └── chat.js
├── images/
│   ├── profile.svg
│   ├── asset-design.svg
│   ├── asset-video.svg
│   ├── asset-brand.svg
│   ├── asset-writing.svg
│   ├── tool-premiere.svg
│   ├── tool-figma.svg
│   ├── tool-obs.svg
│   └── tool-notion.svg
└── data/
    └── portfolio-context.json
```

The structure above describes the expected supporting files referenced by the HTML and configuration. Keep the folders and filenames aligned with those references when uploading the complete project.

## 🚀 Run Locally

1. Download or clone this repository.
2. Keep the supporting `css/`, `js/`, `images/`, and `data/` folders in the locations referenced by the HTML and JavaScript.
3. Open `index.html` in a browser.

For a more reliable local development experience, run a simple local static server from the project folder, for example:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000` in your browser.

## 🌐 Deploy

This project includes a `vercel.json` configuration file and can be deployed as a static website on Vercel:

1. Push the project files to a GitHub repository.
2. Import the repository into Vercel.
3. Keep the project configured as a static site unless your deployment setup requires otherwise.
4. Deploy and test the published site, including navigation, images, theme switching, project filtering, and the contact form.

## ⚙️ Configuration and Security

- Review `.env.example` for any environment variables expected by the project.
- Do not commit real secrets, API keys, or private credentials.
- The contact form currently provides an on-page demo confirmation; the HTML indicates that it does **not** send an email by itself.
- Confirm any API-backed chat functionality and its configuration before deployment.

## 🛠️ Customization

- Replace placeholder profile and asset images in `images/`.
- Update project entries and tags in the relevant JavaScript/data files.
- Add your real GitHub and LinkedIn profile URLs.
- Connect the contact form to a backend or form service if you want to receive messages.
- Update the page title, description, and portfolio copy as your work evolves.

## 👩‍💻 Author

**Divyanshi Rajvansh**  
B.Tech Computer Science and Engineering student interested in software development, data analysis, and digital content creation.

## 📄 License

No license is specified yet. Add a license file if you want to define how others may use, modify, or distribute this project.
