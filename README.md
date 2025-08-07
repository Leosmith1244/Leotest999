# Generic Toastmasters Website Template

This template provides a modern, Toastmasters brand-compliant website for clubs to showcase their activities, attract members, and manage communications. Built with HTML, CSS, Bootstrap 5, and Toastmasters' official colors and fonts, it’s designed for easy customization and deployment using GitHub and Netlify.

## Features
- **10 Pages**: Homepage, About Us, Meetings, Membership, Leadership, Resources, Blog/News, Contact, Gallery/Events, Guest Information.
- **Static Blog**: Includes a sample post, expandable with new HTML files.
- **Meeting Agenda**: Sample agenda in `meetings.html`, editable for weekly updates.
- **Role Signup Form**: Formspree-powered form in `membership.html` for meeting roles.
- **Contact Form**: Formspree-powered form in `contact.html` for inquiries.
- **Responsive Design**: Mobile-friendly with Bootstrap 5.
- **Branding**: Uses Toastmasters colors (`#772432`, `#004165`, `#A9B2B1`, `#F2DF74`, `#FFFFFF`, `#000000`) and fonts (Montserrat, Source Sans 3).
- **Deployment**: Static site, no build command, publish directory `/` for Netlify.

## Files
- `index.html`: Homepage with welcome, mission, and upcoming meetings.
- `about.html`: Club history, benefits, and testimonials.
- `meetings.html`: Meeting schedule, format, and sample agenda.
- `membership.html`: Joining details, benefits, FAQs, and role signup form.
- `leadership.html`: Club officers and their roles.
- `resources.html`: Toastmasters links, speaking tips, and recommended resources.
- `blog.html` & `blog-post-1.html`: Blog with a sample post.
- `contact.html`: Contact form, social media links, and meeting location map.
- `gallery.html`: Placeholder for event photos/videos.
- `guest.html`: Guest expectations and FAQs.
- `styles.css`: Toastmasters-compliant styling.
- `images/`: Folder for assets like the Toastmasters logo.

## Getting Started

### 1. Download and Set Up
- **Download**: Clone this repository or download the zip file:
  ```bash
  git clone https://github.com/[yourusername]/generic-toastmasters.git
  ```
- **Create Repository**: Fork this repo or create a new one for your club (e.g., `[club-name]-toastmasters`).
- **Add Files**: Copy the template files to your repository.

### 2. Customize Placeholders
- Open files in a text editor (e.g., VS Code) and replace placeholders with your club’s details using find-and-replace. Examples:
  - `[CLUB_NAME]`: Your club’s name (e.g., “Savory Toastmasters”).
  - `[FOUNDING_YEAR]`: Year founded (e.g., “2025”).
  - `[MEETING_DAY]`: Meeting day (e.g., “Monday”).
  - `[TIME]`: Meeting time (e.g., “7:00 PM”).
  - `[LOCATION]`: Venue or “Online” (e.g., “123 Main St”).
  - `[CITY]`: City (e.g., “Your City”).
  - `[IN_PERSON/HYBRID/ONLINE]`: Meeting format (e.g., “Hybrid”).
  - `[ZOOM_LINK]`: Zoom URL (e.g., “https://zoom.us/j/your-meeting-id”).
  - `[CLUB_EMAIL]`: Club email (e.g., “info@clubtoastmasters.org”).
  - `[FORMSPREE_ID]`: Formspree form ID (see below).
  - `[FACEBOOK_LINK]`, `[TWITTER_LINK]`, `[LINKEDIN_LINK]`: Social media URLs.
  - `[GOOGLE_MAPS_EMBED]`: Google Maps iframe code.
  - Officer names/emails (e.g., `[PRESIDENT_NAME]`, `[PRESIDENT_EMAIL]`).
  - Blog details (e.g., `[BLOG_TITLE]`, `[POST_DATE]`, `[THEME]`).
  - Gallery details (e.g., `[EVENT_NAME]`, `[EVENT_MONTH]`).
  - `[CURRENT_YEAR]`: Current year (e.g., “2025”).

### 3. Add Assets
- **Logo**: Download the Toastmasters logo from [Brand Portal](https://www.toastmasters.org/resources/brand-portal). Save to `images/` and reference in HTML (e.g., `<img src="images/logo.png" alt="Toastmasters Logo">` in `index.html`).
- **Gallery**: Add event photos/videos to `images/`. Update `gallery.html` with `<img>` or `<iframe>` (e.g., YouTube embeds). Ensure member consent per Toastmasters guidelines.

### 4. Set Up Forms
- Sign up at [Formspree](https://formspree.io) to create two forms:
  - Contact form (`contact.html`).
  - Role signup form (`membership.html`).
- Replace `[FORMSPREE_ID]` in both files with the respective form IDs (e.g., `https://formspree.io/f/your-form-id`).
- Test forms to ensure submissions reach the designated email (e.g., VP of Education for role signups).

### 5. Update Blog and Agenda
- **Blog**: Add posts by creating new HTML files (e.g., `blog-post-2.html`) based on `blog-post-1.html`. Link them in `blog.html`. Update placeholders like `[BLOG_TITLE]`, `[POST_DATE]`.
- **Agenda**: Edit `meetings.html` with weekly details (e.g., `[SAMPLE_DATE]`, `[SAMPLE_THEME]`, `[NAME]`).

### 6. Push to GitHub
- Commit and push changes:
  ```bash
  git add .
  git commit -m "Customize [CLUB_NAME] Toastmasters website"
  git push origin main
  ```

### 7. Deploy on Netlify
- Log in to [Netlify](https://app.netlify.com), select “New site from Git,” and connect your GitHub repository.
- Configure:
  - **Publish directory**: `/`
  - **Build command**: Leave blank (static site).
- Deploy to get a URL (e.g., `[club-name]-toastmasters.netlify.app`).
- Enable continuous deployment for automatic updates.

### 8. Test Locally
- Install Netlify CLI:
  ```bash
  npm install -g netlify-cli
  ```
- Run:
  ```bash
  netlify dev
  ```
- Preview the site to verify styling, forms, and placeholders.

## Maintenance
- **Weekly**: Update `meetings.html` with new agendas.
- **As Needed**: Add blog posts, update officer details in `leadership.html`, or add gallery content.
- **Forms**: Monitor Formspree submissions or switch to Google Forms/Netlify Forms for advanced features.

## Toastmasters Branding
- Uses official colors and fonts per the [Brand Manual](https://www.toastmasters.org/resources/brand-portal).
- Download logos and assets from the [Resource Library](https://www.toastmasters.org/resources/resource-library).
- Ensure photos/videos in `gallery.html` have member consent.

## Support
- For HTML/CSS help, visit [W3Schools](https://www.w3schools.com).
- For branding, refer to [Toastmasters Brand Portal](https://www.toastmasters.org/resources/brand-portal).
- Contact [YOUR_EMAIL] for assistance or share feedback with your District.

## Alternatives
- **FreeToastHost**: Offers Toastmasters-specific features like dynamic agendas but less customizable.
- **WordPress for Toastmasters**: Supports RSVPMaker for agendas/signups but requires separate hosting.

## License
This template is free for Toastmasters clubs to use and modify. Ensure compliance with Toastmasters International’s branding guidelines.