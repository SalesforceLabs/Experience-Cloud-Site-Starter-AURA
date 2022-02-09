# Experience Cloud Site Starter (AURA)
The Experience Cloud Site Starter (AURA) is a mobile 1st site design for a self-service site using best practices (e.g., flexible pages), using no-code, low-code,  CSS, and HTML components.

This package contains:
* **Site Starter (AURA) Template**
    This template provides a clean theme (minimal pages) using flexible layouts for all pages.
    Templates are selected when creating a new site or changing the Template. This will overwrite all site pages and the theme. 

* **Site Starter (AURA) Theme**
    Use to update an existing sites' header styles, hero, and branding.
   
* **Page Templates**
    When creating a page or new page variation, some page templates are included. For non-object and non-CMS page types, a page layout called **Template** is included to get a new page started. 


**Notes:**
1. **Read the instructions carefully** and complete the tasks before publishing. There are additional instructions and details 
2. This package is **supplied as-is** and is not supported by Salesforce.
3. No CMS or Knowledge content included.


## New Site setup

1. Enable and setup Experience Cloud on your site.
   Configure Knowledge and Salesforce CMS (as needed)

2. Install the package - [Experience Cloud - Site Starter (AURA)](https://login.salesforce.com/packaging/installPackage.apexp?p0=04t5f000000iqvo) Spring '22 v1.8 (Template Only)
    
3. Open the **Digital Experiences** app and then open the **All Sites** tab.

4. Click **New**

5. Select **Site Starter (AURA)**

6. Add the site **Name** and site **URL** (optional)


## Site Configuration

1. Go to Experience Builder and configure the themes’s color, images, font, and theme settings.
    
2. Update the Site CSS Experience Builder / Theme / Edit CSS (from the pull-down menu). 
   Copy the CSS from [CSS-Site-Starter-CSS.css](./CSS-Site-Starter.css) and paste it into the sites’ CSS.
    
    **Note**: 
    - CSS can change from release to release and potential can visually impact other components within the Experience Cloud site. 
    - The site CSS is reviewed for each release, but is **supplied as-is**.
    
3. Add to the site’s Head Markup (Experience Builder / Settings / Advanced / Edit Head Markup).
   Copy the Head Markup from [Head-Markup.html](./Head-Markup.html) and paste it into the sites’ Head Markup.
    
4. Allow for the use of Font Awesome icons, add ht&#8203;tp://cdnjs.cloudflare.com to **Setup** / **CSP Trusted Site Definition**, and check **Allow** for font-src and style-src.


## Using Site Starter (AURA) Theme and Page Layouts on existing sites

The package also allows for updating an existing site for theme, page templates, and CSS.
1. To use the same Theme Layouts (e.g., Help Center, Search, Login Wide) as Site Starter (AURA) open your site and change the Theme Layout within Experience Builder under Settings / Theme / Change Theme. Your original theme is still availabel.

2. To use page templates from Site Starter (AURA):
    - New Non-Object Pages: Create a new page and select one of the page template. 
    - Existing Pages: Rename the existing page variation, and create a new one with the original name selecting the cooresponding page layout. 
      If the non-object or object pages do not show a cooresponding page layout, create a new page with a flexible layout. 
    - Make the new page the default and original page can be deleted.    


## For More Information 
- See [Experience Cloud - Site Starter (AURA) Documentation](https://salesforce.quip.com/PjCIAaDQWNGY)
- [Watch the overview video](https://salesforce.vidyard.com/watch/dBMyA254f61Zr5dPWcTta9?)
