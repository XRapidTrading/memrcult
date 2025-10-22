# Image Replacement Guide

## Images to Replace

You need to replace these three image files with the new ones you provided:

### 1. The Offering (First Image - Ritual Scene)
- **Save as:** `client/public/memecult_offering_scene_.png` *(note the underscore at the end)*
- **Your image:** The first image showing the green pepe on the altar with other meme characters around

### 2. The Ritual (Second Image - Red Pepe Scene)  
- **Save as:** `client/public/memecult_ritual_scene.png`
- **Your image:** The second image showing the red pepe character in the center with others around

### 3. The Transformation (Third Image - Single Green Pepe)
- **Save as:** `client/public/memecult_transformation_scene_.png` *(note the underscore at the end)*
- **Your image:** The third image showing a single distressed green pepe character

## How to Replace

1. Open the `client/public` folder in your project
2. Delete or backup the existing three PNG files
3. Save your three new images with the exact names above
4. The images will automatically be used when you rebuild/redeploy

## What Was Fixed

✅ **Netlify Configuration Issue Resolved**
- Changed publish directory from `"dist"` to `"dist/public"` 
- This matches where Vite actually builds the files
- Your site should now deploy correctly without the "Page Not Found" error

## Next Steps

1. Replace the three images as described above
2. Commit and push your changes to trigger a new Netlify deployment
3. Your site should now work correctly!
