# About course

This course will take you on a clear and easy journey through **installation**, **customization**, and **launch** of a WordPress site (without writing a line of back-end code!) so that you can get great-looking websites up and running quickly, whether it's for a client request or for your own use.

- Launch a WordPress site live on the web
- Mock up a WordPress site structure
- Find and install the perfect theme for your needs
- Customize a design to fit your content

>You can find **free WordPress themes** at [Pantheon.io](https://pantheon.io/). 

# Part 1 - Launch and configure WordPress
## What is WordPress?
WordPress is a **CMS**, which stands for **Content Management System**. The platform allows the construction of robust, fully-functional websites at almost any level of complexity.
WordPress created at **2003**.

### Vocabulary
Here are some of the concepts that WordPress includes in its platform. You'll often hear these words in this course; synthesizing the following elements in your site can lead to a project suitable for any personal project or client request.

- **Pages** are one of the two main content types within WordPress. This is a distinct page within a WordPress site that has its own title and content. It can either be the main landing page or a separate page afterwards, like "About" or "Contact." Adding one in WordPress is as easy as clicking a button.
- **Posts** are individual entries that are grouped together on a page. Many WordPress sites feature a main landing page that lists all posts in reverse chronological order. This works great for blog and news sites but less well for other types of content.
- **Plugins** are individually addable functionalities that extend the power of a WordPress site. Some plugin examples include a simple captcha you could add to your site, security boosts, contact forms, image customization, analytics options, and more.
- **Themes** are a group of files and style rules that will determine the look of your site. By choosing and tweaking the right theme, you'll end up with a great color scheme, font collection, and visual feel of your site.

## Launch your WordPress site
A local band, Cat Avalanche, in your city has reached out and is ready to pay you for a live, great-looking website. Here's the band's criteria that involve themes you'll see often with clients, like vague design requests, site structure, etc.):
- The website should have a dark, "underground" feel, made to feel like the visitor is at one of Cat Avalanche's live shows. The band has also sent you a photo from one of their concerts you can use in the design scheme if you want.
- There should be separate pages for the following content: a home page, information about the band, their tour dates, their blog posts, and their contact information.
- The band's logo should be visible on the top left of the page.
- The site navigation should be at the top of the page, not on the sides.
- The band's name, Cat Avalanche, should be in the site URL.

If you're faced with a **one-time project** that probably won't require much technical ongoing maintenance or heavy lifting, it's a great bet to use a tool like Themecloud that takes care of almost everything for you so you can jump right to the product itself (and **appease your client that much quicker**)!

You'll use Themecloud here for the following reasons, instead of other quick installation services. With Themecloud:
- You're not blocked by domain name registration: many WordPress starter kits force you to register a domain immediately, which costs money and can be a mental roadblock since domain registration is such a paid commitment. Instead, Themecloud gives you your own dedicated example.themecloud.me URL so you can have a live site instantly and worry about buying a precise domain later.
- You'll have daily site backups: your site will be backed up every day to Amazon S3, and you can even use these backups as a staging environment to test stuff.
- You'll have access to all themes and plugins: many WordPress managers limit you to only a few themes, but with Themecloud you have access to the full WordPress landscape of themes and plugins (including the ability to customize your HTML, CSS, and even PHP).

>Themecloud has changed its payment policy since the writing of this course; specifically, the free trial has been reduced to 2 days. For a **free alternative**, you can check out [Pantheon.io](https://pantheon.io).

## Configure your WordPress settings
Go to https://example.com/wp-admin/index.php  
![figure 1](./img/dashboard.jpg)
The left-hand navigation menu provides links to all of the WordPress administration screens, with submenu items displayed on hover.  

- **Dashboard** (left menu item) show widgets:
    - **At a Glance** lets you check out the the number of posts, comments, and pages on your site. It also shows which WordPress version you have along with the theme of your site.
    - **Quick Draft** allows you to fire off a post draft with a title and simple content. Just click the blue button, and it'll be saved in your drafts for publishing later. Never miss a spontaneous post idea!
    - **Activity** shows you scheduled posts as well as recently published posts. You'll also see their associated comments with buttons to moderate each comment.
    - **WordPress News** (engine updates news)
- **Settings > General** (left menu item). You should start a project by checking out the following settings options:
    - **Site title** could be a brand, a witty blog name, or something else depending on the ultimate site usage. It will also display as the title in a visitor's browser bar. It's the first thing people will see, so choose wisely (though you can always change it later)! 
    - **Site tagline** supplements the site title. Most WordPress themes display both the site title and the site tagline, but if a tagline is too cumbersome, you'll know how to remove it from a theme by the end of this course.
    - **Date and time settings**, depending on your preferences or culture, you (or your client) might prefer dates and times to displayed in a particular format. This can always be changed later, so when getting started, just choose one you like best.
    - **Language** will change your dashboard language instantly once you save the settings. Consider the language you speak as well as your client's language, if they'll have administrative or writing access.

You can **preview** your site anytime by clicking the site name in the top left corner of the **Dashboard**.
![figure 2](./img/visit_site.jpg)

# Part 2 - Tailor your WordPress site
## Mock up your site structure
The time has come to build out your **site structure**. For new websites that you're building from scratch, it's often a good idea to start your building process with a **content-first** approach. It's all too easy to get lost in design decisions before you actually have any content to work with; while you might end up with a beautiful site template, things can go south when you realize the content you add later doesn't fit everything you've just worked on! It also means that you'll make concessions to your content to fit the design, when it should be the other way around.

>"Designing '**Content First**' is about gathering your client’s assets and laying them out within the design in order of importance, optimizing the content for a web audience and ensuring that the message(s) and/or features that the client wants to get across to their users is consistent across all devices."

Source: Everyday Designer, "Change your focus and design 'Content First'"

>Make **design** work for your **content**, not the other way around!

**In the course example project**, my local band Cat Avalanche asked me to build them a site. Luckily, **they already gave a list of the pages they want present: Home, About, Tour, Blog, and Contact**. Here are some initial thoughts you might have, knowing these content needs:
- There will be 5 total pages;
- Each of these pages has different content types (home = general intro, blog = a lot of text, contact = social networks and possibly a form, etc.);
- Each page should be accessible from the other pages.

The final product is much more imaginable just by knowing the site structure. Already we can picture a navigation bar including these items, how long each page might be, and more. Make sure you get answers to these questions early in your building process so you can design for your content every step of the way.

### Add pages
Let's add pages to our WordPress site.  
On the left of the **Dashboard**, hover over **Pages** and select **All Pages**. Feel free to delete the sample page Themecloud added for you by hovering and clicking **Trash**. Click the "**Add New**" button on the top, to go to the page editor. Build entire pages using simple form!
- **Title** of your page will be added to the site's navigation automatically and will also be the basis of its permalink. Each page title should be unique (makes sense)!
- **Editor** is page's big blank box is where you'll populate the page's content, including text formatting, images, etc.
-  **Administrative options** on the right hand side give you control over the page status (published or not), its visibility, and its associated "parent" pages. 

**Publish**ing each page means it's immediately live online with its own URL, which you can get on the Edit page ("Permalink: ....").

![figure 3](./img/trash.jpg)

![figure 4](./img/add_new_page.jpg)

### Set a homepage
Navigate back to your site landing page. Notice how the home page of the WordPress site still isn't your Home page. **WordPress makes a list of posts the primary home page**, which works well for blog platforms but less well for other uses!

Non-blog sites (or sites that want post content to be elsewhere) will need to **change this default homepage**. To make the Home page you just created the main landing page, navigate to **Settings > Reading**. Under **Front page** displays, check the box that says **A static page**. You can then set a page as the home screen and move the notion of posts somewhere else, like a dedicated blog page.

![figure 5](./img/reading_settings.jpg)

Once you map out your site structure and add the necessary pages to WordPress, you'll find you've done a big chunk of work that leaves you free for the next step: choosing a visual theme.

## Install a WordPress theme
WordPress themes are much more than flimsy design skins! They'll give life to your website and can completely change the display of your content depending on the theme you choose. File types within a theme can include **template** files, **image** files like JPEGs and GIFs, CSS **stylesheets**, and even **PHP code**!

All WordPress pages are made up of three basic elements: a **header**, **content**, and a **footer**.
![figure 6](./img/wp_page.png)

### Choosing a first theme
Navigate to **Appearance** and click **Themes** from the hover menu that appears. On the first page, you have default WordPress themes that are already installed and ready to activate (notice they all say "By the WordPress team" when you click for more details).

Let's explore more themes though, including options made by other developers by clicking the "**Add New**" button up top to access the theme browser. You can explore themes by popularity, chronological order, or simply by relying on WordPress's "Featured" category.

The full breadth of themes can be overwhelming, especially as most of them look pretty okay in their screenshots! I suggest you make sure a particular theme is:
- **Responsive**: make sure the site will look good on multiple device types, not just on desktop. Non-negotiable on today's web!
- **Good ratings**: WordPress shows the average number of stars (1-5) on the theme details window.
- **Customization options**: theme developers will usually mention if their theme offers customization choices like additional fonts, header photo uploads, navigation options, logo support, and more. Not having these customization options means you're pretty locked into the theme design: not ideal if you're trying to tailor design to your content.

Clicking on a theme will launch a window where you'll find theme **details** and a **preview**. The good criteria mentioned above will be listed in the details on the left; if a developer doesn't mention "responsive" in the description, you can bet that theme isn't!

### Install a theme
Once you find a theme that suits you, install it by clicking the blue **Install** button up top! You can install multiple themes without necessarily using them all.

You'll hit an installation screen back on your WordPress dashboard where you'll see the live progress of the theme's installation. You can hit "**Activate**" to apply with your theme immediately, which means you'll be able to preview the theme live on your site with its theme defaults. 

## Tweak your WordPress theme
Our first steps into theme customization will take place directly within the theme customizer, accessible at **Appearance > Customize** in your WordPress dashboard sidebar.  
You'll be looking at modifications to the following menu items:
- Static front page
- Site title/tagline/logo
- Header area
- Footer
- Colors
- Widgets

You'll notice **many themes have very similar customization menus**. Don't be worried: these exercises will be useful no matter which theme you use!
![figure 7](./img/wp_customize.jpg)

### Static front page
One disadvantage of **changing themes** (as we changed from the WordPress default to Sydney) is that **it'll reset your settings about front and post page arrangements**. These are the settings you previously set up in **Settings > Reading** to change which page would be your homepage. No fear though! Since the Sydney customization menu gives me a tab to do this directly, I can just navigate to the bottom of the customization menu, click **Static Front Page**, and re-add "Home" as my front page and "Blog" as my posts page.

### Title, tagline, and logo
Here's where you'll take care of your site's naming situation including its title and tagline (also accessible within your **General Settings**).

Simple **logo upload** is a feature many WordPress themes offer, which is lucky considering that one of the band's criteria was to have their logo in the top left of the website.

In theory, a client would've supplied you with their own logo, but since Cat Avalanche doesn't actually exist (shhhh, don't tell!) I made a logo using [Logomakr](logomakr.io). Knowing how to make a logo is a useful skill.

>Make sure whatever logo you use has a transparent background; otherwise it'll show up as an opaque rectangle or worse!

### Footer
When dealing with large site chunks like headers, footers, and sidebars in WordPress, you should think of their composition as an assembly of content blocks called **widgets**.

You'll arrange content blocks as widgets regardless of which theme you select. In the Sydney theme, the footer customization tab doesn't ask you to add specific content but only to indicate how many widgets (content sections) you'll have.  A list of site pages and some contact information would make a nice footer, don't you think? To include those two elements, I'll select two widgets here and add them later in the flow.

### Colors
All WordPress themes will allow you to change their color schemes, whether through the editor (HTML or CSS) or directly in the theme customizer. How do you select the right colors though?! If you already have images you're using as part of the site you're building, you should select colors that complement the featured images. Alternatively, if you're building a website for a company, make sure you ask what their defined color palette is; they'll usually know the HEX codes (6 digit color codes starting with #) used in their logo and graphical elements!
>To identify specific HEX codes within an image, use a color picker tool in Chrome, Photoshop, or otherwise.

### Menus
From the Menu customization tab, I can add a menu and call it Primary navigation. From there, I'll "Add item," select Pages, and individually add all the pages I want in my upper navigation. I'll check the box to make this my primary menu, which will automatically add it to the top of my site! When adding your own menus, drag and drop to reorder the menu elements left to right. It's also possible to automatically add upper-level pages to this menu by checking the second box.

### Widgets
The Widgets section will, in general, let you divvy up what your widgets are and where you're putting them. My first option in this menu is Sidebar. Personally, I'm a fan of minimal or nonexistent sidebars. I can remove all the existing elements one by one from the Sidebar list, especially since the default blog-related functionalities aren't pertinent for my client, who wants more of a general site.

Next up, do you remember above how we discussed thinking of adding **content blocks** to site chunks like the footer? Now you can actually add the content blocks you want. 

In my second footer widget (Footer 2), I'll select **Text** from the menu so I can add the relevant HTML:
```html
<a href="http://twitter.com">Twitter</a> - <a href="http://facebook.com">Facebook</a> - <a href="http://instagram.com">Instagram</a></p>
<p><strong>Mailing address:</strong></p>
<p>9862 E. 14th St #7A</p>
<p>New York, NY 10014</p>
<a href="mailto:>catavalanchenyc@gmail.com">catavalanchenyc@gmail.com</a>
```

Here's a list of all the possible widgets you could include in a certain area of your site, like the footer or sidebar:
- **Archive**: A monthly archive of your site’s Posts.
- **Calendar**: A calendar of your site’s Posts.
- **Categories**: A list or dropdown of categories.
- **Custom Menu**: Add a custom menu to your sidebar.
- **Meta**: Login, RSS, & WordPress.org links.
- **Pages**: A list of your site’s Pages.
- **Recent Comments**: Your site’s most recent comments.
- **Recent Posts**: Your site’s most recent Posts.
- **RSS**: Entries from any RSS or Atom feed.
- **Search**: A search form for your site.
- **Tag Cloud**: A cloud of your most used tags.
- **Text**: Arbitrary text or HTML.

## Customize a WordPress theme's inner workings
The customizer allowed you to handle many image, organization, and color related tweaks, but the editor will let you get down to the CSS level to change spacing, sizing, and more. The editor is accessed from the left hand menu of our page as usual: **Appearance > Theme File Editor**.

The theme's stylesheet will be open by default, which is called `styles.css`. You can see all available files to edit on the right-hand side. You don't need to worry about all the PHP files you see if backend code isn't really your thing; there's a lot you can accomplish just in CSS within this first file!

The first thing I recommend doing from the editor screen is to copy the contents of `styles.css` and paste them within a text editor. Save this file as `default_styles.css` somewhere on your computer. This way you have a copy of the theme's default styles and can reset any changes you make.

### Identifying elements
Here are several quick introductory tidbits you'll use in your hunt to find certain CSS within a theme's stylesheet.

Theme developers often leave comments within their code to help users understand how it works. A code comment, no matter the language, is text that does not have functionality beyond just being a human-readable note. A CSS comment starts with/* and ends with*/. For example, within the Sydney theme stylesheet, we see a comment like this:
```css
/*--------------------------------------------------------------
Header
--------------------------------------------------------------*/
```
The theme's developers left this comment to introduce the style rules for the theme's header. Feel free to remove comments if you don't find them useful, or add and modify your own!

### Inspect elements
Most HTML elements within a theme are identified with a class or ID. CSS rules then target these classes and IDs, so the right rules are applied to the right elements! You'll need to know how to find the class, ID, or general element type of something on your page so you can then hunt down the relevant style rules. In most browsers, right-click on an element and select "Inspect" or "Inspect element" from the menu that appears. Within these developer tools, you'll see all the HTML associated with a particular element. You could search the stylesheet to find the associated styles with this element, change it and press button **Update**.

>Beware that once you save your changes, you'll no longer be able to rewind your modifications except by copying the default styles from your local copy.

Using this same method:
- Identify an element in the page
- Modify the CSS associated with that element in the theme stylesheet.

### Install a plugin
You've customized your site appearance on a number of levels. You can also extend your site's **functionality** by tapping into the universe of plugins that other WordPress developers have made available to you. For example, my band would like to have a contact form on their Contact page that sends user messages by email. Since this is a common functionality, you can assume that someone else has already made it available as a plugin! Click **Plugins** on the left-side **Dashboard** menu and **Add New**. From there, you can search "contact" or whatever other functionality you seek.

I'll select "Contact Form Clean and Simple," since that's exactly the functionality I seek! Clicking "**Install Now**" will install the plugin, and after installing any plugin you need to also click **Activate** on the next screen. This new plugin now appears within my list of all plugins, and I'll click **Settings** in order to customize the plugin for my needs.