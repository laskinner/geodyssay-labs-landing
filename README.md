# Welcome to the Readme for the Geodyssey Labs landing page!
![image](https://github.com/laskinner/geodyssay-labs-landing/assets/1858258/d3d74ee0-74a7-4ae7-868e-a4f5ffd211f7)

Site author: Luke Skinner

Link to [livesite](https://laskinner.github.io/geodyssay-labs-landing/)

# Site goal
The goal of this site is to introduce potential customers to Geodyssey Labs, and the product Geodyssey Labs is building Caliper. As Caliper is not built, in meant only to be a high-level overview with general highlights of benefits to the customer.

# Phases of development
1) Decide on Geodyssey Labs as project
2) Establish basic structure and text
3) Styled and designed first for mobile and in grayscale
4) Add color
5) Add responsivity
6) Testing
   
# Purpose
The purpose of this site is to serve as the first iteration of a landing page for a ConstructionTech startup called Geodyssey Labs.

# Features and Structure

## Landing page
The purpose of the landing page is meant to simply introduce the user to Geodyssey Labs, and more broadly its geomonitoring importance in keeping the public safe.

![image](https://github.com/laskinner/geodyssay-labs-landing/assets/1858258/3c339010-e54f-4769-90f8-d8b7ced8a516)

![image](https://github.com/laskinner/geodyssay-labs-landing/assets/1858258/c05d5853-b1d8-4d09-af1b-a62c282ee2f3)

## Team
The purpose of the team page is to introduce to Geodyssey Labs team and instill in the user confidence that we the team building Caliper are experienced and capable.

![image](https://github.com/laskinner/geodyssay-labs-landing/assets/1858258/b6e0b791-5ae5-462a-bffb-a55018ef2398)

![image](https://github.com/laskinner/geodyssay-labs-landing/assets/1858258/9ef24202-bd42-40c8-a41b-93ccc3bbc40c)

## Product
The purpose of the product page is to introduce the user to Caliper, Geodyssey Labs' first product, and its potential use cases so that users understand under which environments Caliper is meant to operate.

![image](https://github.com/laskinner/geodyssay-labs-landing/assets/1858258/df60e737-835e-4220-b5ca-d1411cb2acd4)

![image](https://github.com/laskinner/geodyssay-labs-landing/assets/1858258/01d4969d-7571-4dc5-9497-96ec633d233f)

## Sign Up
The purpose of the signup page is to provide users with the ability to sign up for Caliper.

![image](https://github.com/laskinner/geodyssay-labs-landing/assets/1858258/10196f33-e638-45ef-9dc9-d4899bceb96e)

![image](https://github.com/laskinner/geodyssay-labs-landing/assets/1858258/3885cd5a-1e59-4971-a179-9e5487f9f1cc)

# Deployment
The site is deployed using Github pages. To deploy, simply push code into Main, and the site will automatically redeploy upon merge.

To deploy from scratch:
- Navigate to Settings
- Select "Pages" from the left navigation menu
- Select "Main" branch
- Click Save

# Changes and Challenges
## Borders vs Cards
One major was the overall look and feel of the site. While attempting to introduce cards and containers to provide more modern styling, and make the site look and feel less "HTML-y", cards, borders, and shadows were introduced. The first settled-upon iteration looks as follows:


![image](https://github.com/laskinner/geodyssay-labs-landing/assets/1858258/91b76eb2-b401-4411-8aa4-ede76a758991)


While this looked good, it still felt like it needed improvement. Therefore, eliminating borders, introducing subtle shadows, and changing the body background give it more depth:


![image](https://github.com/laskinner/geodyssay-labs-landing/assets/1858258/83ebe078-489c-497c-8d06-6a099349a47e)

## Links vs Buttons
Another challenge was the webpack styling taking over the styling of buttons which were meant to simply link to other pages, as can be seen at the bottom of the screenshot below. The button would look fine were it not for the text getting styled as a link inside the button. The purpose of the buttons was to prompt users to navigate to the next section of the website, offering a logical flow that would result in a sign-up. However, in the interest of time, we'll hide the buttons to reintroduce them later.


![image](https://github.com/laskinner/geodyssay-labs-landing/assets/1858258/d478013d-014e-4130-a993-948b859c5a57)

## Link breaks vs CSS
Throughout the code, there are a few line breaks to provide additional spacing between elements. In the future, it would be worth the effort to see if, in the interest of correctness, these line breaks could be replaced with proper padding and margin.
![image](https://github.com/laskinner/geodyssay-labs-landing/assets/1858258/c2ceaf06-13cb-4763-9a91-3fbdd95f0bde)

![image](https://github.com/laskinner/geodyssay-labs-landing/assets/1858258/a01c36d8-f029-446e-9f5c-ad97a43e4d75)

# Won't Do
Three tasks were deemed not necessary due to their being largely aesthetic, less important than other fixes, and therefore deprioritized than other adjustments that needed to be made to make the deadline.

## Social Media links
In some views, particularly those on larger viewports, the social media links began to be space across the inter footer, which doesn't look nice.
![image](https://github.com/laskinner/geodyssay-labs-landing/assets/1858258/20dae4d5-5917-44ea-934f-e38fa3e325ba)

## Terms of Service, Privacy Protection, Copyright
As with the social media links, this was also deprioritized. However, adding these links and functionality could be coupled with a redesign of the social media links, as both share the footer.

## List styles
Some of the lists may perhaps have appeared more readable if they were either in a centered container with left-align or in the case of the Bermadinho Disaster, placed into a table with the left column being aligned right and the right column being aligned left:
![image](https://github.com/laskinner/geodyssay-labs-landing/assets/1858258/513db0ea-0d25-420e-8767-4b19a73f9e63)

Color could have also been added to the left column to provide better readability, as well.

# Tools and Technologies
The only tools and technologies used were HTML and CSS.

# Validation
Jigsaw Validator results

![image](https://github.com/laskinner/geodyssay-labs-landing/assets/1858258/585fe692-5565-47e3-a866-1a7d203c942c)

NU HTML Checker

Index.html:

![image](https://github.com/laskinner/geodyssay-labs-landing/assets/1858258/9c2e7ee9-0844-4828-b6ee-dd96f81f5f2f)

Product.html:

![image](https://github.com/laskinner/geodyssay-labs-landing/assets/1858258/74294d27-14e3-473d-a0dd-6dc3b64996c8)

Signup.html:

![image](https://github.com/laskinner/geodyssay-labs-landing/assets/1858258/4c3c9aad-aaa6-48d3-80f1-7b42313dd109)

Team.html:

![image](https://github.com/laskinner/geodyssay-labs-landing/assets/1858258/ab1804e4-2826-4e24-8c5f-1cd6aaf21891)

# Testing

Thorough testing was conducted on Safari, Chrome, and Firefox. The tests were entirely manual, and much of the testing was focused on responsivity. In the later stages of the project, one can see the testing for responsivity begin with the commit names focusing heavily on fixing bugs around responsivity.

![image](https://github.com/laskinner/geodyssay-labs-landing/assets/1858258/b9514cf6-9f53-4550-b894-8693efc628df)


# Future Development
Future development will include:
- E-mail confirmation sign-up
- Product screenshots
- Copyright, Terms of Service, and Privacy Policy in footer
- Dark and Light mode
- Contact page
- About page to replace team page

# Credits and Attribution

## Content
Much of the content for the landing page was supplied by a pre-existing business plan and pitch deck, created by site author, Luke. This includes everything from company description, tagline copy, use cases, product descriptions, and team bios. Screenshots from the used slides are as follows:
### Brumadinho Dam Disaster
![image](https://github.com/laskinner/geodyssay-labs-landing/assets/1858258/33d37c74-aa94-4515-9d40-e4dc332320de)

### What is Geomonitoring?
![image](https://github.com/laskinner/geodyssay-labs-landing/assets/1858258/825e046c-c2b6-4957-942a-de43c8c38071)

### Product
![image](https://github.com/laskinner/geodyssay-labs-landing/assets/1858258/a6e07e6c-7712-4f0e-b61b-10c5a614879f)

### Team
![image](https://github.com/laskinner/geodyssay-labs-landing/assets/1858258/fe3455f0-4e91-4c61-86ff-5a1da72ed43c)

### Keywords
The keywords chosen for the landing are based on generally accepted suggestions for SEO marketing. A healthy mix of broad, specific, and long-tail keywords is used. They were generated by Bard after providing it with the full company business plan.

### Icons
The icons in the footer were taken from [Font Awesome](https://fontawesome.com/), and code was adapated from Code Institute.

## Media
The image used on the landing page, in the "What is geomonitoring" section is from [Topcon Positioning Systems](https://www.topconpositioning.com/de/vermessung/monitoring).

The photos used in the Use-case section of the Product page are from: [Pixabay](https://www.pixabay.com)

### Use cases credits
- New Construction: Image by [joffi](https://pixabay.com/users/joffi-1229850/?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=1359136)
- Structural Health: Image by [Pexels](https://pixabay.com/users/pexels-2286921/?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=1834754)
- Campaign-Monitoring: Image by [12019](https://pixabay.com/users/12019-12019/?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=79691)
- Mining: Image by [horjaraul](https://pixabay.com/users/horjaraul-495898/?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=481754)
