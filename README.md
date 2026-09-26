# 🎬 Netflix Clone

![Netflix Clone Banner](https://assets.nflxext.com/ffe/siteui/vlv3/9c5457b8-9ab0-4a04-9fc1-e608d5670f1a/710d74e0-7158-408e-8d9b-23c219dee5df/US-en-20210719-popsignuptwoweeks-perspective_alpha_website_small.jpg)

A fully responsive, full-stack Netflix clone application built to replicate the core UI and functionality of Netflix. This project dynamically fetches movie data from the TMDB API, handles user authentication, and includes trailer playback functionality.

---

## ✨ Features

- **User Authentication**: Secure Login/Sign-up functionality (via Firebase).
- **Dynamic Content**: Fetches the latest trending movies, top-rated shows, and genre-specific lists using the [TMDB API](https://www.themoviedb.org/documentation/api).
- **Trailer Playback**: Automatically finds and plays the official YouTube trailer when a user clicks on a movie poster.
- **Responsive Design**: Fully optimized for mobile, tablet, and desktop viewing.
- **State Management**: Efficiently manages user state and movie data across the application.

## 🛠️ Tech Stack

- **Frontend**: React.js, HTML5, CSS3 / TailwindCSS
- **Backend / Auth**: Firebase (Authentication & Firestore)
- **API**: TMDB (The Movie Database) API & YouTube Data API
- **HTTP Client**: Axios
- **Deployment**: Vercel / Firebase Hosting (optional)

---

## 🚀 Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing.

### Prerequisites

Before you begin, ensure you have the following installed:
- [Node.js](https://nodejs.org/) (v14 or higher)
- npm or yarn
- A free API key from [TMDB](https://www.themoviedb.org/documentation/api)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/DHYEY2703/Netflix-clone.git
   cd Netflix-clone
