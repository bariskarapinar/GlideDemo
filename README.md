# GlideDemo

A simple Android application demonstrating how to use the **Glide** library to load and display images from the web.

## What this project does
This project showcases different ways to load images using Glide:
- **Basic Loading**: Fetching an image from a URL and displaying it in an `ImageView`.
- **Image Transformations**: Applying transformations like `circleCrop()` and `fitCenter()`.
- **Placeholders & Error Handling**: Showing a placeholder image while loading and an error image if the request fails.
- **Caching & Optimization**: Using `diskCacheStrategy` and `override()` to optimize image loading and memory usage.

## What is Glide?
In simple terms, **Glide** is a "helper" library for Android that makes it incredibly easy to show images in your app. 

### Why use it?
- **It's Easy**: You can load an image with just one line of code.
- **It's Fast**: It handles all the complex background work (downloading, resizing, and memory management) so your app stays smooth.
- **It Saves Data**: It automatically caches images so they don't have to be downloaded every time the user opens the app.
- **It Prevents Crashes**: It manages memory efficiently to prevent "Out of Memory" errors when dealing with large images.

---
*Created as a demonstration of Glide integration in Android.*
