
This repository forked from revou-fsse-5/milestone-1-regaruzianto

Wlizzard is a game company profile website, containing information about the games currently being developed and news about those games.The site covers news, development updates, and specific details about each game in their portfolio.

This website consists of a header, main, and footer. The header includes a logo, navigation menu, and buttons for login and download. The main section features home, news, and feature games sections. The website is deployed on Netlify with a custom domain purchased from Niaga Hoster.

# Website Structure

## Header
- Logo
- Navigation menu
- Login button
- Download button

## Main Section
- **Home**: Introduction or landing page content
- **News**: Updates and announcements about their games
- **Feature Games**: Information about key games in development or release

## Footer
- Additional navigation
- Contact information
- Other relevant links

#DEPLOYMENT

# Deploying from GitHub to Netlify

## Steps to Deploy

### 1. Connect GitHub Repository to Netlify
- **Login to Netlify**:
  - Go to [Netlify](https://www.netlify.com) and log in using your credentials.

- **Create a New Site**:
  - Once logged in, click on **'New site from Git'** button.
  - Choose GitHub as your Git provider.
  - Authorize Netlify to access your GitHub repositories if prompted.
![deploy a new site](Assets/deploy%20add%20new%20site.png)

- **Select Repository**:
  - Netlify will display a list of your GitHub repositories.
  - Select the repository you want to deploy.
![select repository](Assets/netlify%20deploy%20from%20github.png)

- **Configure Settings**:
  - Choose the branch you want to deploy.
  - Set the build command (if needed) and the directory where the build output resides.
![select branch](/Assets/select%20branch.png/)

- **Deploy Site**:
  - Click **'Deploy site'**.
![deploy](/Assets/deploy%20site.png)

### 2. Configure Build Settings (if required)


### 3. Monitor Deployment

![dashboard](Assets/dashboard.png)

### 4. Automatic Deployments (Optional)
- Enable continuous deployment to automatically deploy your site whenever you push changes to your GitHub repository:

### 5. Custom Domains (Optional)
- If you have a custom domain:
  - Go to **'Site settings > Domain management'**.
  - Add your custom domain and configure DNS settings.
  - In domain hosting set up Name server from netlify
![add custom domain](Assets/domain%20management.png)


# Custom Domain Setup on Netlify

### Step 1: Access Domain Settings in Netlify
### Step 2: Add Your Custom Domain
### Step 3: Verify Domain Ownership
![dns record](/Assets/dns%20record.png)
### Step 4: Update DNS Settings with Your Registrar
![name server](/Assets/name%20server.png)
![name server](/Assets/name%20server%20niaga.png)
### Step 5: Verify DNS Configuration
### Step 6: Set Your Custom Domain as Primary (Optional)



