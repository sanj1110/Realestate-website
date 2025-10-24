# Elite Property Consultancy Website

A professional real estate consultancy website with grey, light red, and white theme.

## Pages Included

- **Home Page** (`index.html`) - Main landing page with services, testimonials slider, and contact info
- **About Us** (`about.html`) - Company information, team, and values
- **Our Approach** (`approach.html`) - Methodology and process details
- **Awards & Recognitions** (`awards.html`) - Industry awards and certifications
- **Book Consultancy** (`booking.html`) - Appointment booking form
- **Contact Us** (`contact.html`) - Contact information and inquiry form

## Features

- Responsive design for all devices
- Vertical contact tabs on right side (home page)
- Testimonial slider with photos and navigation arrows
- Footer with vertical navigation and social media links
- Service cards with hover effects
- Professional color scheme (Grey, Light Red, White)

## How to Deploy to GitHub Pages

### Method 1: Using GitHub Web Interface (Easiest)

1. **Create a GitHub Account** (if you don't have one)
   - Go to [github.com](https://github.com)
   - Click "Sign up"

2. **Create a New Repository**
   - Click the "+" icon in the top right
   - Select "New repository"
   - Name it: `property-consultancy` (or any name you prefer)
   - Make it **Public**
   - Click "Create repository"

3. **Upload Your Files**
   - Click "uploading an existing file"
   - Drag and drop all the HTML files:
     - `index.html`
     - `about.html`
     - `approach.html`
     - `awards.html`
     - `booking.html`
     - `contact.html`
   - Click "Commit changes"

4. **Enable GitHub Pages**
   - Go to your repository Settings
   - Scroll down to "Pages" in the left sidebar
   - Under "Source", select "Deploy from a branch"
   - Select branch: `main` (or `master`)
   - Select folder: `/ (root)`
   - Click "Save"

5. **Access Your Website**
   - Wait 2-3 minutes for deployment
   - Your site will be available at: `https://YOUR-USERNAME.github.io/property-consultancy/`

### Method 2: Using Git Command Line

```bash
# Navigate to the folder containing your HTML files
cd /path/to/your/files

# Initialize git repository
git init

# Add all files
git add .

# Commit files
git commit -m "Initial commit - Real Estate Consultancy Website"

# Add your GitHub repository as remote
git remote add origin https://github.com/YOUR-USERNAME/property-consultancy.git

# Push to GitHub
git branch -M main
git push -u origin main
```

Then follow steps 4-5 from Method 1 to enable GitHub Pages.

### Method 3: Using GitHub Desktop (For Beginners)

1. Download and install [GitHub Desktop](https://desktop.github.com/)
2. Sign in with your GitHub account
3. Click "Create a New Repository on your hard drive"
4. Choose a name and location
5. Copy all HTML files to that folder
6. In GitHub Desktop, you'll see all files listed
7. Add a commit message and click "Commit to main"
8. Click "Publish repository"
9. Follow steps 4-5 from Method 1 to enable GitHub Pages

## Custom Domain (Optional)

If you want to use your own domain (e.g., www.yourcompany.com):

1. Buy a domain from any registrar (GoDaddy, Namecheap, etc.)
2. In your repository, create a file named `CNAME` (no extension)
3. Add your domain name to this file: `www.yourcompany.com`
4. In your domain registrar's DNS settings, add these records:
   - Type: A, Host: @, Value: 185.199.108.153
   - Type: A, Host: @, Value: 185.199.109.153
   - Type: A, Host: @, Value: 185.199.110.153
   - Type: A, Host: @, Value: 185.199.111.153
   - Type: CNAME, Host: www, Value: YOUR-USERNAME.github.io
5. Wait 24-48 hours for DNS propagation

## Updating Your Website

Whenever you need to update the website:

1. Edit the HTML files locally
2. Upload the updated files to GitHub (replace the old ones)
3. Changes will automatically appear on your live site within a few minutes

## Need Help?

- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [GitHub Pages Quickstart](https://docs.github.com/en/pages/quickstart)

## License

© 2025 Elite Property Consultancy. All rights reserved.
