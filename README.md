# Dotnotes Repository

Welcome to the Dotnotes repository! 🚀 This space is dedicated to our community discussions, issue tracking, and the development of Dotnotes.

## Table of Contents

- [Creating Issues](#creating-issues)
- [Using Discussions](#using-discussions)
- [What is Dotnotes?](#the-inspiration-behind-dotnotes)
- [How Dotnotes Works](#how-dotnotes-works)

## Creating Issues

If you encounter a bug 🐞, have a feature request 🚀, or want to suggest an improvement 💡, creating issues is the way to go. Follow these steps:

1. Go to the [**Issues tab**](../../issues).
2. Click on the "**New Issue**" button.
3. Choose the appropriate template (Bug Report, Feature Request, etc.).
4. Fill out the required information and submit the issue.

Please be descriptive and provide as much context as possible to help us understand and address the matter efficiently.

## Using Discussions

Discussions are a great way to engage with the community, share your experiences 🌐, and seek help. Here's how you can participate:

1. Navigate to the [**Discussions tab**](../../discussions).
2. Browse existing topics or start a new one.
3. Choose the relevant category for your discussion.
4. Share your thoughts, ask questions, or contribute to ongoing discussions.

We encourage a positive and collaborative environment, so feel free to share your insights and experiences related to Dotnotes.

---

# Welcome to Dotnotes - Your One-Stop Solution for Academic Excellence!

At Dotnotes, we're committed to providing a comprehensive solution to all your academic needs. Whether you're seeking free study material, notes, previous year question papers (PYQs), video playlists, and more – Dotnotes is your go-to platform for academic success.

## The Inspiration Behind Dotnotes

Dotnotes was born out of a shared frustration among a group of four students from NIEC who recognized a common challenge in their academic journey – the lack of consistent and concise study material. Driven by the need for a centralized platform that could cater to the academic needs of students, they embarked on a mission to create Dotnotes.

## Our Mission

**"One stop solution to all your academic needs. Free study material, Akash, Video Playlist and more..."**

We are on a mission to simplify your academic journey by providing a seamless and organized experience. Dotnotes is not just a website; it's a step towards success, a virtual companion designed to streamline your learning process.

## Features at a Glance

- **Free Study Material:** Access a vast repository of study materials curated for various subjects and academic levels.

- **Notes:** Dive into concise and informative notes crafted to enhance your understanding of key concepts.

- **Previous Year Question Papers (PYQs):** Sharpen your skills by practicing with PYQs, a valuable resource for exam preparation.

- **Video Playlists:** Immerse yourself in curated video playlists that complement your learning experience.

## How Dotnotes Works

Dotnotes operates by utilizing the Google Drive V3 API, effectively transforming Google Drive into a file system. We navigate this virtual landscape for notes using file IDs, similar to inodes in Linux systems. To address latency issues, our Flask/ASP.NET backend employs Redis caching. Notably, one of us took the initiative to rewrite the backend API in ASP.NET – a seemingly unnecessary and stupid enhancement. The frontend is built using React, providing a standard and reliable user interface. Our blog, constructed with Hugo as a Static Site Generator, incorporates TinaCMS for straightforward content management. The backend is hosted on an Azure WebApp instance, while the frontend resides on Vercel. To ensure security and optimize performance, Dotnotes integrates with Cloudflare. The android app is the solo efforts of [@Dhruvgera][Dhruvgera], written in flutter, it uses the same backend API as our webapp. It wouldn't have been possible without [@lakshayGMZ][lakshayGMZ]'s efforts in writing most of the frontend code and experimenting with new features. [@AnishHazra][AnishHazra] and [@Nandini-0703][Nandini-0703] worked on the frontend design for dotnotes, while [@Nandini-0703][Nandini-0703] also working on the other features as well.

It took a lot of efforts building the database from scratch, including a lot of automation scripts, scrappers, spiders (for instance [@martian0x80][martian0x80]'s `spidermap` scraps the dotnotes api to automate sitemap updates), and scripts that are responsible for organizing and maintaining the filesystem tree. In summary, Dotnotes employs a combination of technologies and strategic hosting to provide a seamless and efficient platform for all your academic needs.

---

## Authors
- [@martian0x80][martian0x80]
- [@lakshayGMZ][lakshayGMZ]
- [@Dhruvgera][Dhruvgera]
- [@Nandini-0703][Nandini-0703]
- [@AnishHazra][AnishHazra]

[martian0x80]: https://github.com/martian0x80
[lakshayGMZ]: https://github.com/lakshayGMZ
[Dhruvgera]: https://github.com/Dhruvgera
[Nandini-0703]: https://github.com/Nandini-0703
[AnishHazra]: https://github.com/AnishHazra
