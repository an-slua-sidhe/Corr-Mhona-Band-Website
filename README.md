![Corr Mhóna Banner Logo](assets/images/banner-logo1.jpg "Corr Mhóna Banner Logo")

# **THE _CORR MHÓNA_ BAND WEBSITE**

## **Introduction**

This is the repository for the official **Corr Mhóna** website.

The **Deployed Version** of the site can be visited by clicking [**here**](https://an-slua-sidhe.github.io/milestone-1/).

It was designed by me, **Paul Quinn**, to give the band a greater independent online presence. I initally designed and developed the site from the ground up as part of my [Fullstack Web Development Diploma](https://codeinstitute.net/courses/) with the **Code Institute**, Ireland. The end goal is to provide a fully interactive website for the band, with e-commerce functionality.

The band already had an online presence through third party sites such as [Bandcamp](https://corrmona.bandcamp.com/) and [Facebook](https://www.facebook.com/corrmhona/). However, there was a desire to cut out the middle man and provide the band's fans with the means to quickly and easily access merchandise, information and gig announcements on a single platform. As a band member myself, I decided to undertake this task with the skills I had learned during the course.

A variety of features have been implemented already, and there are several more to come in the near future. I have used the band's own assets to populate the site and inspire its design. There is a full overview of the design/development process below, along with an extensive outline of the testing process, future features, user stories, responsivity and deployment.

## **Table of Contents**

1. [User Experience](#user-experience)
    - [User Stories](#user-stories)
        - [The Band Member](#the-band-member)
        - [The Music Fan](#the-music-fan)
        - [The Promoter](#the-promoter)
        - [The Journalist](#the-journalist)
        - [The Record Label](#the-record-label)
    - [Wireframes](#wireframes)
        - [Basic Wireframes](#basic-wireframes)
        - [Full Asset Mockups](#full-asset-mockups)
    - [Design Choices](#design-choices)
        - [Images](#images)
        - [Colours](#colours)
        - [Fonts](#fonts)
        - [Icons](#icons)
    - [Design Changes](#design-changes)
        - [General](#general)
        - [Mobile](#mobile)
        - [Desktop](#desktop)

2. [Features](#features)
    - [Existing Features](#existing-features)
        - [Common Features](#common-features)
        - [Home](#home)
        - [Biography {'The Band'}](#biography)
        - [Discography](#discography)
        - [Contact](#contact)
    - [Future Features](#future-features)
        - [Contact Form](#contact-form)
        - [Shop](#shop)
        - [Flip Cards](#flip-cards)

3. [Technologies Used](#technologies-used)
    - [HTML](#html)
    - [CSS](#css)
    - [Adobe XD](#adobe-xd)
    - [VSCode](#vscode)
    - [Github](#github)
    - [Javascript](#javascript)
    - [Bootstrap](#bootstrap)
    - [Canva](#canva)
    - [Favicon](#??)
    - [Font Awesome](#font-awesome)
    - [HTML Code Checker](#html-code-checker)
    - [CSS Code Checker](#css-code-checker)

4. [Testing](#testing)
    - [Developer Tools](#developer-tools)
        - [Chrome](#chrome)
        - [Firefox](#firefox)
        - [Internet Explorer](#internet-explorer)
    - [User Scenarios](#user-scenarios)
        - [Listening to New Music](#listening-to-new-music)
        - [Finding out the Latest News](#finding-out-the-latest-news)
        - [Purchasing Merchandise and CDs](#purchasing-merchandise-and-cds)
        - [Hearing the New Album](#hearing-the-new-album)
        - [Finding Out About the Band](#finding-out-about-the-band)
        - [Contacting the Band](#contacting-the-band)

5. [Deployment](#deployment)
    - [Media Queries](#media-queries)
        - [Mobile](#mobile)
        - [Tablet](#tablet)
        - [Desktop](#desktop)

6. [Credits](#credits)
    - [Content](#content)
    - [Media](#media)
    - [Acknowledgements](#acknowledgements)

___

## **User Experience**

**Corr Mhóna** has always prided itself on following a few founding principles; Making use of natural elements both musically and lyrically, organically combining whatever styles suit the music we write, promoting the Irish language, and avoiding narcissistic imagery and remaining grounded when connecting with out fans.

I have tried to use these principles when creating a User Experience for our website, constructing a site that has clean organic lines and colours, that delivers relevant content to the user simply and efficiently, and that is also available in the Irish language.

### **User Stories**

There are a number of different types of user which may visit the site, each with different goals and motivations. I have listed them below in five categories; The Band Member, The Music Fan, The Promoter, The Journalist, The Record Label.

#### The Band Member

- As band member, I can easily put the latest information up on the **News** section of the [**Home**](index.html) page, so that fans and promoters are kept updated.
- As band member, I can embed media from the latest project in the **Media** section of the [**Home**](index.html) page, to make the latest release more exciting and interesting for our fans.
- As band member, I can advertise that the band is available for gigs and festivals through the [**Contact**](contact.html) page of the site.
- As band member, I will eventually be able to add merchandise and CDs to the **Shop** page, so I can sell directly to the fans.

#### The Music Fan

- As a music fan, I can find out everything I need to know about the band in one place, when I search for new music to listen to.
- As a metal music fan specifically interested in Celtic/Gaelic/folk music, I can find the band site through certain keywords found throughout the site.
- As a music fan who has been recommended the band by a friend, I can find everything I need on the site (through the [**Biography**](bio.html) {'The Band'} & [**Discography**](disc.html) pages) to decide whether the band is for me.
- As a music fan who has seen the band live, I can get a clear idea of the bands sound through listening to music on the **Audio Player** or watching the **Teaser Video** in the **Media** section.
- As a music fan who already knows/likes the band, I can check the **Home** page for the latest news on gigs and upcoming releases, and I will soon be able to visit the **Shop** page to puchase the latest merchandise and CDs.
- As a music fan, I can get in touch with the band on the [**Contact**](contact.html) page and let the band know why I am making contact through the **Contact Form**.

#### The Promoter

- As promoter, I can check the **News** section to see if the band are currently active and looking for gigs.
- As promoter, I can use the [**Contact**](contact.html) page to get in touch with the band, and specifically let them know that I am interested in booking them for gigs via the **Contact Form**.

#### The Journalist

- As journalist who has been sent a copy of the latest CD to review, I can get more information about the band to complete my review by visiting the [**Home**](index.html), [**Biography**](bio.html) {'The Band'} & [**Discography**](disc.html) pages of the site.
- As journalist who is completing a feature about the band, I can find more information from the same locations mentioned above, as well as finding extra musical and visual content in the **Media** section, as well as the [**Biography**](bio.html) {'The Band'} & [**Discography**](disc.html) pages.

#### The Record Label

- As a record label employee who has been sent a promo pack from the band, I can browse the site to get a feel for the ethos and imagery the band is looking to evoke.
- As a record label employee who has been recommended the band by another professional or promoter, I can get in contact with the band via the [**Contact**](contact.html) page and specifically tell the band the reason I am making contact through the **Contact Form**.

### **Wireframes**

I used Adobe XD to design and create **Wireframes** for the site. It was decided to have a multi-page site from the beginning, as well as to follow the the principal of **Mobile First**. I followed the usual method of keeping the basic wireframes extremely simple stylistically, mostly focusing on the form, location and interaction between the various elements of the site on each page. I then used the band's assets to decide on the colour palette, theme and artistic direction of the site.

#### Basic Wireframes

The basic **Wireframes** are available within this repository in two PDFs; one for [Mobile](assets/wireframes/wireframes-mobile.pdf) and one for [Desktop](assets/wireframes/wireframes-desktop.pdf). There is a separate wireframe for each of the four site pages in each PDF. Any colour used is for contrast only. Simple text headings were added to each element to denote its purpose. These overall [**Design Choices**](#design-choices) can be traced to the final deployed [**Website**](https://an-slua-sidhe.github.io/milestone-1/), with some changes (see [**Design Changes**](#design-changes)).

#### Full Asset Mockups

The full library of **Corr Mhóna** assets were added to the project when the **Mockups** were created. This gave me a clear art direction along with a library of high quality art and imagery which was ready to go. The mobile mockup can be found [here](assets/wireframes/mockups-mobile.pdf) and the desktop version is [here](assets/wireframes/mockups-desktop.pdf). Wireframe choices followed, main body of work was deciding which assets to place where. Final PDFs were of such high quality (due the size of the art assets) that I had to resize them before I uploaded them to the repository.

### **Design Choices**

#### Images

As the band relates to and promotes natural imagery in their music and art, it was an obvious choice to do the same with the website. There was a substantial back catalogue of artwork, but the art for the new album was chosen as the foundation of the site, with other images used to enhance where necessary. The superb [__*Dair*__](#assets/images/dair-art.jpg) album cover was used as the main **Hero Image** for the **Landing Page**, with a [**Banner Logo**](#assets/images/banner-logo1.jpg) used at the top of the other pages. The new album [poster art](#assets/images/dair-dryad.jpg) and a [live photo](#assets/images/band-live2jpg) of the band were included in the [**Home**](#index.html) page **Media** section. A photo of each band member was included in the **Band Member** section of the [**Biography**](#bio.html) {'The Band'} page. All three Corr Mhóna CD covers were used in the [**Discography**](#disc.html) page, whereas the new album poster art was used as a background image for the [**Contact**](#contact.html) page.

#### Colours

I was inspired by the new album's [**Cover Art**](assets/images/dair-art.jpg), and this is the basis for the colour scheme and palette for our site. I used [**Canva**](https://www.canva.com/) to create a palette, and I added accent colours of forest green and maroon red so the site would engage the visitor at first glance. I sought a subtle contrast between the different element's shades, using maroon or forest green to accentuate elements on first glance or on hover (see the [**Home**](#index.html) page **CTA** {Call to Action} for an example of this). **Navbar** & **Social Media** links transition to maroon on hover, whereas **in-line** links in the body of the text are initially maroon and hover to grey, so that they stand out from the surrounding text (all of these features can also be seen on the [**Home**](#index.html) page). The **Navbar** has an opaque background on scroll for legibility, but a translucent background otherwise. The **Gaeilge** link in the **Navbar** is black and hovers to maroon, but this changes to a white which hovers to bright red when the **Navbar** is scrolled (so it continues to be visible).

#### Fonts

I used [**Google Fonts**](#https://fonts.google.com/) to find a font for the site. Handwritten or more natural looking fonts (such as the Irish language [*Cló Gaelach*](http://www.nualeargais.ie/foghlaim/seanchlo.php?teanga)) were considered first, as it was believed they would suit the band ethos more. However, these were not practical in execution, as the more detailed script was hard to read. [*Gafata*](#https://fonts.google.com/specimen/Gafata) was chosen as the main font in the end, as it has some organic charateristics, but is clearly legible as either a heading or the main text of section. The back up font is *Sans-serif*.

#### Icons

A bespoke Corr Mhóna navicon was created for the site, using [??](). Social media link icons were supplied by [Font Awesome](#https://fontawesome.com/).

### **Design Changes**

#### General

- **Contact Page Background**  
    The original [**Contact**](#contact.html) page was considered unsatisying and boring in comparison to the other pages, once the site was fully constructed. A new style was chosen for the **Contact** page therefore, with the new album [Poster Art](#assets/images/dair-dryad.jpg) being used as an atmospheric background for the page's **Section**.

- **Corr Mhóna Live Photo**  
    A different [**Live Photo**](#assets/images/band-live2.jpg) was chosen, as this shows the band playing at the [**Siege of Limerick**](http://siegeoflimerick.net/). This echoes the story in the **News** section about **Corr Mhóna** playing at the festival.

- **Discography Order**  
    The chronological order of the discography releases was swapped, with the earliest recording (__*An Chéad Thríail*__) appearing at the top of the [**Discography**](#disc.html) page. This was becaue the art for __*Dair*__ has been used extensively elsewhere, and the so other covers can provide some variety here.

#### Mobile

- **CTA Position**  
    Though the original wireframe design had the molbile version of the **CTA** between the **Burger Menu Button** and the **Audio Player** at the top of the Landing Page, it didn't look well in practice. It was decided to keep the same **CTA** format throughout all resolutions.

- **Audio Player**  
    The **Audio Player** did not look well on mobile resolutions, and was removed.

- **Irish Language Option**  
    The **_Gaeilge_** (Irish language) link did not work well with the mobile **Burger Menu Button**, and now displays at higher resolutions only.

- **Copyright Text**  
    This text only appears on tablet or desktop, as it was decided that the **Social Media** links looked better centralised by themeselves on mobile.

#### Desktop

- **Translucent Navbar**  
    Though the original wireframes show a cream-coloured background for the **Navbar**, a translucent background was chosen for the finished site, as this compliments the parchement style of the **Hero Image** and **Banner Logo**.  This is not visible on mobile, where the **Navbar** becomes a **Burger Menu Button**.

- **Contact Page Navbar**  
    On 1500px or higher the [**Contact**](#contact.html) page **Navbar** become opaque as soon as the page loads, and the **Banner Logo** does not display. This showcases the background artwork on larger resolutions.

___

## **Features**

There are four pages on the site, with a number of features appearing on each page and certain features being unique to one page. The basic layout of the site was created using the [**Bootstrap 4**](#https://getbootstrap.com/) grid system (which is based on [Flexbox](#https://www.w3schools.com/css/css3_flexbox.asp)), with some alterations and additions.

### **Existing Features**

#### Common Features

- **Navbar**  
    I modified the typical [**Bootstrap**](#https://getbootstrap.com/docs/4.0/components/navbar/) **Navbar** to suit the site, which included fixing it to top so it would remain there while scrolling, with a translucent background. I modified [Javascript] from [**JS Fiddle**](#https://jsfiddle.net/wamosjk/ufhp9s15/) to make an opaque background for when the page scrolled. The __*Gaeilge*__ (Irish language) link changes colour from black to white on scroll, whereas the **Audio Player** text does not display. All of these  keep the text legible when scrolling.
    The **Navbar** turns into a **Burger Button Menu** on mobile, and this changes colour on scroll for visibility, also enabled with the same **Javascript** code.

- **Gaeilge Link (Irish Language Option)**  
     This link was coding inside the **Bootstrap Navbar** div mentioned in the previous section. The description of how it changes when scrolled can be found above. A separate Irish language **HTML** page was created for each of the four main pages ([index_ga.html](#index_ga.html) e.g.). This link, available on every page, allows the user to navigate between the Irish and English versions of the site. All text (including image descriptions and alternative text), the **HTML** language setting (i.e. html lang="ga") and headings were translated into the Irish language by me. Link changes to maroon on hover, from black to white on scroll, and does not display on mobile for aesthetic reasons.

- **Audio Player**  
    A basic **HTML Audio Player** was included to the right of the **Header**. This contains a sample from the upcoming album, which is available in both [**MP3**](#assets/audio/dair.mp3) and [**OGG**](#assets/audio/dair.ogg) format. Some text advertising the player can be seen beneath it. The player does not appear on the mobile version of the site. The audio player text disappears when scrolled. This text was not included on the [**Contact**](#contact.html) page as the **Navbar** is already in its scrolled form when the page loads.

- **Banner Logo**  
    All other pages besides the **Home** page display a [**Banner Logo**](#assets/images/banner-logo1.jpg) instead of the **Hero Image**. On the [**Contact**](#contact.html) page the **Banner Logo** is not displayed above 1500px (see [**Media Queries**](#media-queries) below).

- **Section**  
    There is a main section on each page, though the content is different each time (see below). These were created using the **Bootstrap** grid and are constructed with containers, rows and columns. The [**Home**] and [**Biography**] pages main sections consist of two main containers which can display side by side or one beneath the other, depending on whether they are viewed in mobile of desktop (see [**Deployment**](#deployment)). The [**Contact**](#contact) and [**Discography**](#disc.html) pages have slightly different section layouts, however. All **in-line** links within any page's section text are fully navigable; they appear as maroon but change colour to grey when hovered over.

- **Footer**
    A basic footer can be found on each page. It contains two features, some **Copyright Text** and the **Social Media Links**. The **Copyright Text** is a simple part of the **Bootstrap** grid, and doesn't display on mobile. The **Social Media Links** are fully functional, and link to the band's previously existing online web presence on [**Bandcamp**](#https://corrmona.bandcamp.com/), [**Youtube**](#https://www.youtube.com/watch?v=2wL0o1rxRLQ), [**Facebook**](#https://www.facebook.com/corrmhona/) and [**Instagram**](#https://www.instagram.com/corrmhona/). The icons for each social media platform were provided by [**Font Awesome**](#https://fontawesome.com/).

#### Home

- **Hero Image**  
    This [image](#assets/images/dair-art.jpg) is the new album cover, and provides a stiking backdrop to the **Landing Page**. It is presented via a **Jumbotron**, and scales across all platorms.

- **Call to Action (CTA)**  
    There is **CTA** at the bottom of the [**Landing Page**](#index.html) envelope. This tells users that a new album is coming soon, and provides a link for them to click to get more information, bringing them to the **News Section** of the page.

- **Media Section**  
    This section contains an embedded [**Youtube** video](#https://www.youtube.com/watch?v=228sZcdZ6O0) that plays a **Teaser Video** with a medley of tunes from the new album. There are also a couple of images in this section; the new album [poster art](#assets/images/dair-dryad.jpg) and a [live photo](#assets/images/band-live2jpg) of the band.

- **News Section**  
    There are three elements containing text in this section. These display the latest news about the band. The third element ('Corr Mhóna play the Siege of Limerick') does not display on mobile to make the site more compact.

#### Biography

- **Band Members Section**  
    This [element](#bio.html) contains photos of the four band members and their names. It displays to the left for desktop and to the bottom on mobile and tablet.

- **Biography Section**  
    This is an [element](#bio.html) which contains a large amount of text. All links within the text navigate to their respective targets. The **Biography Section** displays to the right for desktop and to the top on mobile and tablet.

#### Discography

- **Discography Section**  
    There is only one main section container in the [**Discography**](#disc.html) page. There are three groups of elements within it, each group with an **Album Cover**, an **Album Title** and **Album Text**. These are displayed on a dark green background, from the oldest release to the newest. On higher resolutions, the three elements appear in a containing div with a sand-coloured background, whereas on mobile the appear separately from the top down (i.e. **Album Cover**, **Album Title**, **Album Text**).

#### Contact

- **Contact Section**  
    This section is different to the other three pages. There is a large background image (the new album [**Poster Art**](#assets/images/dair-dryad.jpg)) and a central element on an opaque background. This contains a [**Contact Form**](#contact.html) which is not functional yet, but will be in future. It is a modified version of the [**Bootstrap**](#https://getbootstrap.com/docs/4.0/components/forms/) form code. The form has several fields which ask the user to let the band know why they are getting in touch; an e-mail field, a set of three radio buttons, and a larger text input field. There is a [**Bootstrap**](#https://getbootstrap.com/docs/4.0/components/buttons/) button below these features, which has been modified so that its colours (maroon and cream) match the site.

### **Future Features**

#### Contact Form

The contact form needs **Javascript** to be fully functional. There are a couple of instances of Javascript code on this site, but I have yet to start learning the language, and so the ability of the **Contact Form** to receive and transmit information via a server will be part of a future expansion.

#### Shop

As with the **Contact Form** above, the **Shop** page needs **Javascript** to function. It is one of the major benefits of the band having its own site, and will provide the band with 100% profit from sales. Currently the **Shop** option in the **Navbar** is crossed out and inactive, but a future iteration of this project will use **Javascript** to make a fully functional and interactive e-commerce page for the site.

#### Flip Cards

This is another possible future feature for the site, though a purely aesthetic one; making images and photos function as **Flip Cards**. Each flip card would have extra information about whatever the image contained. This would make the site more dynamic and enjoyable for the user.

___

## **Technologies Used**

All the technologies used to create this project are listed below, along with their usage. Simply click on the title for a link to the main site. When there were separate instances where a technology was used, I have listed each link below.

### [**HTML**](#https://en.wikipedia.org/wiki/HTML5)

- This project's structure is based on **HTML 5**.

### [**CSS**](#https://en.wikipedia.org/wiki/Cascading_Style_Sheets)

- This project's style was created using **CSS 3**.

### [**Adobe XD**](#https://www.adobe.com/ie/products/xd.html)

- The wireframes and mockups for this site were designed in **Adobe XD**.

### [**VSCode**](#https://code.visualstudio.com/)

- All code for this site (including this README file), and all **Github** versioning of this code, was done using **VSCode**.

### [**Github**](#https://github.com/)

- Versioning of this project was done through **Github**.

### [**Javascript**](#https://en.wikipedia.org/wiki/JavaScript)

- **Javascript** was used a couple of times when creating this site.
    - There were [three plugins](#https://getbootstrap.com/docs/4.3/getting-started/introduction/) required so **Bootstrap** would function; **jQuery**, **Popper.js** and **Bootstrap's** own **min.js**.
    - I also copied and modified **Javascript** code from [**Js Fiddle**](#https://jsfiddle.net/wamosjk/ufhp9s15/) to create transitions while scrolling.

### [**Bootstrap**](#https://getbootstrap.com/)

- The site was built using **Bootstrap's** grid system. I also modified several **Bootstrap** components.
    - [**Navbar**](#https://getbootstrap.com/docs/4.0/components/navbar/)
    - [**Buttons**](#https://getbootstrap.com/docs/4.0/components/buttons/)
    - [**Contact Form**](#https://getbootstrap.com/docs/4.0/components/forms/)

### [**Canva**](#https://www.canva.com/)

- I found my colour palette by uploading the new album [**Cover Art**](#assets/images/dair-art.jpg) to **Canva**, and added to this with my own colours.

### [**Favicon**](??)

- ??

### [**Font Awesome**](#https://fontawesome.com/)

- The **Social Media Icons** were supplied using **Font Awesome**.

### [**HTML Code Checker**](#https://validator.w3.org/)

- I checked my HTML with the **W3C Markup Validation Service**

### [**CSS Code Checker**](#https://jigsaw.w3.org/css-validator/)

- I checked my CSS with the **W3C CSS Validation Service**

### [**CSS Auto-prefixer**](#https://autoprefixer.github.io/)

- The **Autoprefixer CSS Online** provided a **Vendor Prefix** check for my code.

___

## **Testing**

### **Developer Tools**

#### Chrome

#### Firefox

#### Internet Explorer

### **User Scenarios**

#### Listening to New Music

#### Finding out the Latest News

#### Purchasing Merchandise and CDs

#### Hearing the New Album

#### Finding Out About the Band

#### Contacting the Band

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

___

## **Deployment**

### **Media Queries**

#### Mobile

#### Tablet

#### Desktop

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.

___

## **Credits**

### **Content**

- The text for section Y was copied from the [Wikipedia article Z](https://en.wikipedia.org/wiki/Z)

### **Media**

- The photos used in this site were obtained from ...

### **Acknowledgements**

- I received inspiration for this project from X
