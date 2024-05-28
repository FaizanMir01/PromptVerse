# PromptVerse

PromptVerse is a modern web application designed for discovering, sharing, and managing AI prompts. Built with a sleek and contemporary glassmorphism design, it provides a visually appealing and user-friendly experience. 

## Features

- **Modern Design with Glassmorphism Trend Style**: Enjoy a modern and visually appealing interface with a sleek, glass-like design.
- **Discover and Share AI Prompts**: Browse AI prompts shared by the community and create your own to share with others.
- **Edit and Delete Created Prompts**: Manage your prompts with the ability to edit and delete them as needed.
- **Profile Page**: View and manage all the prompts you've created in your own dedicated profile page.
- **View Other People's Profiles**: Explore the profiles of other users and discover the prompts they've shared.
- **Copy to Clipboard**: Easily copy AI prompts to your clipboard for quick use.
- **Search Prompts by Specific Tag**: Find prompts related to specific topics using the tag-based search functionality.
- **Google Authentication using NextAuth**: Securely log in with your Google account using NextAuth.
- **Responsive Website**: Enjoy a seamless experience across all devices, from desktops to smartphones.
## <a name="tech-stack">⚙️ Tech Stack</a>

- Next.js
- MongoDB
- NextAuth
- TailwindCSS

  **Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone https://github.com/FaizanMir01/PromptVerse.git
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env` in the root of your project and add the following content:

```env
NEXTAUTH_URL=http://localhost:3000
NEXTAUTH_URL_INTERNAL=http://localhost:3000
NEXTAUTH_SECRET=
GOOGLE_ID=
GOOGLE_CLIENT_SECRET=
MONGODB_URI=
```
