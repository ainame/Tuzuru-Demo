# Tuzuru Demo Blog

This is a demonstration blog showcasing the capabilities of [Tuzuru](https://github.com/ainame/Tuzuru), a static blog generator CLI tool written in Swift.

## 🌟 What This Demo Shows

This demo blog demonstrates key Tuzuru features:

- **Content Organization**: 20 blog posts organized into 6 topic-based directories
- **Publication Date Management**: Posts distributed across dates from 2017-2025 using Tuzuru's `amend` function
- **Automatic Category Pages**: Directory-based organization with automatic navigation
- **Git Integration**: Proper commit history showing amend functionality
- **Static Site Generation**: Clean HTML output with responsive design

## 📂 Content Structure

Posts are organized into these categories:

- **Technology** (4 posts): Machine Learning, Cryptocurrency, Digital Privacy, Mindful Tech Use
- **Lifestyle** (4 posts): Remote Work, Minimalism, Time Management, Building Habits  
- **Health & Wellness** (3 posts): Sleep Optimization, Home Workouts, Indoor Plant Care
- **Creative Skills** (4 posts): Travel Photography, Creative Writing, Language Learning, Coffee Brewing
- **Finance & Career** (2 posts): Personal Finance, Freelance Success
- **Environment** (3 posts): Sustainable Cooking, Urban Gardening, Climate Change

## 🚀 Live Demo

The demo blog is automatically deployed via GitHub Actions to GitHub Pages: [View Demo](https://ainame.github.io/tuzuru-demo/)

## 🛠 How This Demo Was Created

1. **Initialized** a new Tuzuru blog with `tuzuru init`
2. **Created** 20 diverse blog posts covering various topics
3. **Organized** posts into topic-based directories under `contents/`
4. **Amended** publication dates using `tuzuru amend --published-at` to distribute posts from 2017-2025
5. **Set author** to "tuzuru" for all posts using `tuzuru amend --author`
6. **Generated** the static site with `tuzuru generate`
7. **Deployed** via GitHub Actions to GitHub Pages

## 📋 Running Locally

To regenerate this blog locally:

1. Install [Tuzuru](https://github.com/ainame/Tuzuru)
2. Clone this repository
3. Run `tuzuru generate` to build the site
4. Open `blog/index.html` in your browser

## 🤖 AI-Generated Content Notice

All blog posts in this demo are AI-generated content created for demonstration purposes only. Each post includes a disclaimer at the top indicating this.

## 📄 License

This demo project is provided as an example of Tuzuru's capabilities. The content is for demonstration purposes only.

---

**Powered by [Tuzuru](https://github.com/ainame/Tuzuru)** - A Swift-based static blog generator