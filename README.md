# Beta Supplies
## This project is designed to highlight what I have learnt so far from HTML, CSS and Bootstrap. It also combines my love of climbing and shopping for climbing supplies. 

## UX:

### 1. Strategy

This website is designed to be used by climbers, to be efficient in the finding of equipment and the latest information. 

I want the site to be a place where people interested in climbing can connect to buy the latest equipment, find deals, learn what's happening in the sport through the use of blogs and links to social media, and as a result I want to create a space to connect to the climbing community. 


### 2. Scope

- Multiple pages including Home Page, Product Pages, Contact and Blog. 
- Jumbotron featuring image, from Bootstrap Library
- Social media links in the footer and on the contact page


### 3. Structure

One of my main aims with my structure was to ensure that people could find what they wanted and to get them there within the fewest number of clicks. My navbar is simple and easy to understand, with the product dropdown including the product pages. I also include featured items, clearence items and blog post in the home page. 

My second aim was to ensure that visitors to the site new exactly what the site was for. This I tried to ensure with the name of the site, Beta Supplies, the term Beta being a well used phrase within the climbing community. I also included a brief and clear summary within the navbar. 

I want the site to be responsive across platforms, so I have used Bootstrap and Flexbox to do this. 

https://github.com/OllieMedley/ms1.2/tree/master/wireframe

### 4. Skeleton

- I used a navbar with a responsive structure that becomes a burger icon at mobile level, otherwise it is clearly layed out with an efficient dropdown for the product pages. 
- The Beta Supplies Icon also brings you back to the home page. 
- Social media links are on every page and displayed with their icons.


### 5. Surface

Colors: 

I chose colors that were quite bold and dark. I wanted the feel to be simplistic and rugged, so I decided on grey to be the major color with everything else set to contrast this and give the text more weight and for the user to be more drawn to the information. 

Fonts:

The fonts were chosen for similar reasons to the colors, I wanted them to be rugged but I also wanted it to be clear that it contained useful information. I went for Bangers to give the rugged appeal, I decided on Encode becuase it had a level of professionalism that reminded me of Times New Roman, this gave me the impression that what would be written would be trusted more. 
Overall I wanted a feel of work and play to come through, it is a fun sport that people do take seriously. 

Imagery:

The images that I chose were chosen because of what they displayed, I wanted them to be representative of what was being discussed. With the exception of the Jumbotron image, I chose this not only because of what it showed but because it was colorful, striking and a juxtoposition to the simplistic colors used elsewhere.  

### User stories:

Below are user stories for visitors to the site.

1/ As a visitor to the site, I want to find the latest deals on climbing supplies, so that I can afford better equipment.

2/ As a visitor to the site, I want to be able to see the latest information. 

3/ As a visitor to the site, I want to know what the site is for.

4/ As a visitor to the site, I want to be able to navigate and easily find what I'm looking for.

5/ As a visitor to the site, I want to be exposed to items that I wasn't expecting but are of interest to me. 

6/ As a visitor to the site, I want to be able to easily find contact information. 

7/ As a visitor to the site, I want to have easy access to the social links for the company. 


### Wireframes: 
https://github.com/OllieMedley/ms1.2/tree/master/wireframe

I removed the search bar from the header and the radio buttons from the product pages as I felt they would be there just to be there, and it isn't something I wanted. Once I am able to add funcitoning versions it may be somehting I look at adding in. 

The typography that I chose was designed to be more rustic and reminisent of rock face, which is why I chose Bangers, I chose Encode as a juxtaposition to this to display factually correct information. 

![responsive screenshot](https://github.com/OllieMedley/ms1.2/blob/master/assets/wireframe/responsivescreenshot.JPG)

### Features

- Jumbotron featuring image, from Bootstrap Library
- Social media links in the footer and on the contact page
- Flexbox display in the product pages
- The link in the jumbotron uses a linear gradient which switches as you hover and changes the pointer icon to the pointer implying a click. 

### Features Left to Implement

Search bar in header once there is a database attached
Radio buttons, again once a database is attached. 

### Technologies Used
Languages:
-HTML
-CSS
-Javascript

### Libraries and Integrations: 
-Google fonts (for typography)
-FontAwesome (for the icons)
-Bootstrap (used for the header, jumbotron, grid layout and cards)

### Workspace: 
-Brackets.IO

-GitHub 

-Git

-Balsamiq

## Testing
### Validation
I used W3C validation for HTML, this brought up one error relating to the jumbotron in index.html, the error related to the use of a tag around a button which isn't best practice. To solve this I rewrote the html to use <a> and styled this with css to make this look like the similar Bootstrap button.
 
1 error was found with my CSS with the Jigsaw Validator but this is relating to the list of colors which is only there for ease when selecting colors

### Manual Testing
I followed all of the links on the site to ensure that they went where they should. 

I checked the responsiveness of the website on Responsitor. It displays the site on different devices both landscape and portrait, which I found to be helpful.

I also used Googles DevTools as I went along, this is how I first discovered that I had applied the wrong bootstrap cdn. Non of my pages were scaling and it's certainly taught me to make a note of the correct CDN's. 

I viewed my website in various browsers to ensure that everything had displayed correctly; I used: Google Chrome, Firefox, Opera, Microsoft Edge.

I have used Lighthouse ![lighthouse](https://github.com/OllieMedley/Beta-Supplies/blob/master/assets/wireframe/Lighthouse.JPG)

Lighhouse report brings up that the image aspect ration isn't natural. If I was to take the site live and use it professionally I would have taken images myself that would have ensured that the natural aspect ratio was uniform and wouldn't need to be ammended. However I used free images from istockphotos.com which had different aspect ratios. 

Lighthouse also brings up resolution which is linked to the aspect ratio. 

### User Story Tests:

1/ As a visitor to the site, I want to find the latest deals on climbing supplies, so that I can afford better equipment.
- This is something that I wanted to be at the forefront of the site, which is why I built a Jumbotron for this. The Jumbotron for me fits the purpose, it is bright and it's intention is clear. The button doesn't go anywhere, if I was to take this site live I would have build a separate product page for this.

-Viewed on mobile, I removed the Jumbotron. This was becuase it took up space that detracted from the remaining site, if taken forwards professionally I would add the link to the page in the dropdown and set it apart from the other links. 

2/ As a visitor to the site, I want to be able to see the latest information. 
- The Blog space appears clearly on the home page and on the separate blog.html page. In both the summaries are easy to read and respond well across platforms. 

3/ As a visitor to the site, I want to know what the site is for.
- I think this is the clearest, from the pun type name to the introductory statement in the navbar. I also checked with multiple people to ensure the intended audience was clear. 

4/ As a visitor to the site, I want to be able to navigate and easily find what I'm looking for.
- The navbar is easy to operate, I considered how many clicks were required to take you to where the user wanted to be and tried to ensure it was as few as possible.  

5/ As a visitor to the site, I want to be exposed to items that I wasn't expecting but are of interest to me.
- This is the reason for the home page layout, the featured items and the blog snippets are something that I know climbers are drawn to. We love the latest gear, news and tips. That's why I gave the two equal weight on the homepage and made them site side by side. 

6/ As a visitor to the site, I want to be able to easily find contact information. 
- Issues soemtimes occur and you want to get hold of soemone to help. I made sure that social links could be found on every page and created a contact page for emails and phone number. I also took artistic liberty with the social links on this page to give weight to the sites social media presence as a serious option to get in touch with the sites operators. I ensured all of the links worked in terms of taking you somewhere, in this case they had a target of blank, I also ensured that the hoer effect worked nicely. 

7/ As a visitor to the site, I want to have easy access to the social links for the company. 
- As above, I provided social links on every page. More so with this user story, I want to keep visitors interested in the brand and have access across multiple sites so that I have a better chance of drawing them back to the site. 

### Bugs: 

#### Bug 1

I had an issue with the footer background not extending through the footer on mobile, there was a break in the color when the viewheight was at 50. The actual code was: 

box-shadow: 0 100vh 0 50vh #3d3232;

I changed this to: 

box-shadow: 0 100vh 0 100vh #3d3232;

This meant that the background color extended from the top of the footer to the bottom across all platforms. 

#### Bug 2
I did have a lot of trouble with the layout of my product cards, the cards kept lining up in a single row which I attempted to fix using Bootstrap grid layout. This didn't solve the issue so I played around with Flexbox for the first time. 

.product{
    display: flex;
    flex: flex-end;
    }
    
This attempt did not work and after some research and playing around with it I came to this solution: 

.product-wrap {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content:center;
    }

After this the product cards reacted as I wanted, they were positioned appropriately on the page and were responsive across platforms. 

## Deployment
To write the code I used Brackets.IO 

All of the written code was pushed to the master branch of github repository.

I selected the master branch as a source file in the settings menu. 

Once selected, this publishes the project to GitHub Pages and displays the site URL.

There aren't any differences between the deployed version and the source. 

The code can be run locally through clone or download.

You can do this by opening the repository, clicking on the 'Code' button, and selecting either 'clone or download'.

### The site is published at https://olliemedley.github.io/Beta-Supplies/


## Credits
### Media
The photos used in this site were obtained from myself - the image for the jumbotron or from www.istockphoto.com - a very helpful site ad one image from Climbing Gear Reviews - https://www.google.com/url?sa=i&url=https%3A%2F%2Fclimbinggearreviews.com%2F2020%2F03%2F12%2Fscarpa-veloce-review-2020%2F&psig=AOvVaw3tkYzoQuLOmypvKSFvDL25&ust=1605963981954000&source=images&cd=vfe&ved=0CAMQjB1qFwoTCJjRzpeYke0CFQAAAAAdAAAAABAD

### Balsamiq
Used to create the wireframes

### Bootstrap
(used for the header, jumbotron, grid layout and cards)

### Acknowledgements
I received inspiration for this project from Epic TV and Depot Climbing and help from my mentor
