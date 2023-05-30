# Investments A.I

Welcome to Investments AI, an innovative investment firm that revolutionizes the way you invest. We harness the collective expertise of seasoned investors and highly skilled AI specialists to conduct thorough analysis, meticulous study, and precise predictive calculations. Our investment team and AI specialists collaborate closely to ensure we make well-calculated risk-to-reward investment decisions.

At Investments AI, we cater to both small and large-scale investors who are ready to embrace the power of artificial intelligence alongside traditional investment markets. Statistics demonstrate that investments guided and monitored by our AI bots have a significantly higher chance of thriving compared to the outdated traditional investment methods.

Our investment firm is particularly advantageous for new and intermediate investors who prefer a more balanced risk profile. Unlike other firms that promote high-risk, high-reward strategies, our approach ensures a guaranteed return on your investment within a year. We prioritize safeguarding our clients' investments, significantly reducing the likelihood of loss compared to traditional investment models.

The undeniable success of "Investment bots" in the crypto exchange markets exemplifies their superiority in consistently achieving favorable profit margins compared to individual investors. Therefore, why not capitalize on the best of both worlds?

At Investments AI, we pride ourselves on delivering exceptional service and offering an ironclad guarantee. Trust us to take your investments to new heights with our cutting-edge approach and unwavering commitment to your success.

![Responsice Mockup](https://github.com/Blaize-Egelhof/Project_1/blob/main/media-for-readme/business-candle-stick-graph.png)

## Features 

In the section below I will highlight each section of my website and explain its purpose , as well as why I have decided to implement each section and feature ! 

### Existing Features

- __Navigation Bar__

  - Featured on all 4 pages .
  - This section will allow my potential investors to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button. 
  -Each Navigation bar is different depending on what page you are on. IE , if a users on the sign-up page , the sign-up a link will be removed and vise versa.
  -In my Navigation bar I have a sign-up link , login link and meet-the team link . 
  -I have chosen to incorporate these links with the following ideas in mind:
     *As a potential investor who may be interested in signing up and finding out more about our services we offer it is a given to have a sign-up link in order to make direct contact between our team and our potential clients. 
     *As an investor who is already a client of ours a login page is needed in order for our client to login to their uniquily setup account to view their investments. 
     *Finally , regardless of if you are an existing client or potential client , we have a page dedicated to our 2 main teams who work with our clients investments , this page introduces a more welcoming and anti-corporate approach which to typical investment firm , with the intent of painting our firm as more open , trustworthy and friendly!  

![Nav Bar](https://github.com/lucyrush/readme-template/blob/master/media/love_running_nav.png)

- __The landing page Section__

  - This landing page includes a very suttle hero image with a white text overlay with 2 anker links. 
  - The anker links are included to give a user the option to sign-up OR login if the user has already decided to do business     
    with my investment firm after reading the main text included on the landing page.
  - This section gives a very clear explanation about who we are as an investment firm.
  - I am aware of the contrast errors given when using WAVE on the landing page. I have chosen to include the errors for  
    aesthetic purposes as the background doesnt reduce visability of the text while keeping everything clean and simplistic.

![Landing Page](https://github.com/lucyrush/readme-template/blob/master/media/love_running_landing.png)

- __Why Choose Us Section__

  - This section consists of a static background image with text and 2 anker tags .
  - This section was designed with the following questions in mind , "Why Choose our investment firm over others?" "What makes  
    our investment firm unique?"
  - These questions are quickly answered by the short and simple paragraph explaining what makes us the ideal choice over other 
    investment firms. 
  - I purposely included the same links mentioned in the landing page in the rare scenario that a potential client may have 
    already decided to do business with us after reading the why choose us section of our index page, and would like to sign-up or alternativly login if they are existing clients! 
  - This section is valuable to investors who seek a clear answer to the above mentioned questions without the need of redundant 
    and/or unessary information as many investment firms incorporate in the attempts to "Hide any clause's and/or valuable   
    information which may contridict earlier statments" This plays a big part in my attempt to appear as transparent , honest and trustworthy as possible . 

![Why Choose Us Section](https://github.com/lucyrush/readme-template/blob/master/media/love_running_ethos.png)

- __Meet The Head Team Section__

  - This section is to show the names and faces of our  VIP members who represent Investments AI to all potential and current   
    cliental. 
  - In this section there are 3 different profiles seperating images , names and their respective titles.
  - This again plays into the idea I am trying to communicate honesty , transparency and trustworthyness to all clients . With  
    the idea of seeing the main faces of the people who manage your money as an investor gives you a greater sense of relief as there is a person to blame if something goes wrong , but also emphasis that we as an investment firm have nothing to hide from our investors , indirectly building trust with our clientale. 
  - I have decided to keep the page as simple as possible and to get straight to the point in order to help accomadate potential 
    new investors who are skeptical about giving their money to our firm. 

![Meet The Head Team Section](https://github.com/lucyrush/readme-template/blob/master/media/love_running_times.png)

- __The Footer__ 

  - A footer section that contains the phone number and email address to directly get in contact with us. 
  - This footer section is valuable to users who have more questions that need to be answered before they even consider signing  
    up with us. This way they do not have to complete the sign-in form in order to get in contact. This gives them options for contacting us ! 

![Footer](https://github.com/lucyrush/readme-template/blob/master/media/love_running_footer.png)

- __Sign Up Form__

  - This form is dedicated to present a sign up form which contains a simple form that is intended for first time users signing  
    up  
  - This section is valuable to first time potential clients who want to sign up and further enquire about plans etc. 

![Gallery](https://github.com/lucyrush/readme-template/blob/master/media/love_running_gallery.png)

- __Login Form__

  - This section is dedicated to present a login form to any existing cliental who wish to login to their private accounts.

![Login Form](https://github.com/lucyrush/readme-template/blob/master/media/love_running_signup.png)

### Features Left to Implement

- A seperate dedicated page which can pull client data from a server side and display it for exsting clients who Login.
- I am unable to implement such a page due to time contraints and lack of knowledge about back-end data management as well as 
  JavaScript
- A static page which lets users know that they have succesfully submitted the Sign-Up form to avoid users filling in forms       multiple times , I have not implemented this design due to time constraints.

## Testing 
-Globally applicable sections:
Header:
In my home page I have included a simple heading that contains a heading and 3 anker tags,all anker tags accross all pages have a white background to provide contrast to the suttle background used in the heading section, I have also included aria-labels for users who are visually impaired. the goal I had for the header is to provide a clear and understandable way of navigating though my website without using the back button built into browsers. I have done so by ensuring each anker element uses the correct URL and does not open a new page when clicking on the anker tags as opening multiple tabs while navigating through 1 website can be frustrating for users. I have written media queries located in style.css to responsivly adapt to all viewport sizes between 330px - 1920 px, ensuring the header looks good regardless of viewport width.I have also ran this section through WAVE and have gotten no errors. 

-footer: 
In this footer I have chosen to keep it simple to adhere to my general theme of simplicity , I have included a h2 label with 2 paragraph tags which hold my companys phone number and email address , I have chosent to include 2 font awesome icons to help add some clarity to users as to what they must do with the given information. I have tested my footer section using WAVE and have gotten no errors. I have also included media queries to ensure the footer is still responsive covering viewports 330px-1920px.

-Index.html : 
-Body: 

Who we are section : 
In this section I have included a background image with with a simple heading and paragraph which have been aligned to the left.
The goal of this section is to answer the question most people ask when visiting a new investment firms website , which is "who are these people?" "What makes this investment firm special? " , this section is to answer the first question. I have included a short paragraph briefly describing as the name suggests who we are , with 2 anker tags below the paragraph, I have included aria labels for both anker tags for visually impaired users my goal for these anker tags is to provide options for users once they have read the content , if they decide to do business with us theres a sign up link , if they are currently existing clients who cant find the login form theres a login link righ next to it ! . I have tested this section using WAVE and have chosen to ignore the contrast errors for aesthetic purposes as it doesnt reduce readability of the text while keeping with my websites general look. I have also included media queries for this section to ensure all viewers can view this section confortable using viewports ranging between 330px-1920px . 

Why choose us section: 
In this section the goal is to be answering the 2nd question mentioned "What makes this investment firm special? " This section includes a suttle static background image with a centered container displaying all worded content answering the above mentioned question. 
Again I have included 2 anker tags with aria-labels for users with vision impairments to easily browse through my site.  My reasoning for including the 2 anker tags below the paragraph is to help users navigate to the sign up page if they are sold by our first 2 sections , I have included a login anker tag if already existing clients somehow forget where the login form link is , first shown in the header section. I have tested this section using WAVE and have gotten NO mentioned issues.Additonally I have also included media queries covering viewport sizes 330px-1920px to ensure this section shows on almost all screen sizes.

Meet Our Head Team section: 
In this section I have chosen to openly show my investment firms main head team with the intent of further enphisising transparency , trustworthyness and simplicity to our new or existing clients. I have realised that most new investors will always be hesident to give a firm their hard earned money with the hopes that they will see the money again and any given period of time. This section is to help link faces to our company to provide a better public image of trust which is vital to my type of business. I have included a 3 Containers which hold the image and tital of each head team member . I have tested the section using WAVE and have chosen to ignore the 3 contrast errors for again aesthetic purpose's and as the text's readability isnt affected by its chosen grey background. Additionally I have added media queries to this section to cover viewports between 330px-1920px.

### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator] , upon scanning each .html file present. 
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator] , upon scanning each .css file present.
### Unfixed Bugs

No definitive bugs present 
You will need to mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a big variable to consider, paucity of time and difficulty understanding implementation is not a valid reason to leave bugs unfixed. 

## Deployment

How I deployed this site using Github Pages

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - I started a repository using Github and cloned it to CodeAnywhere to use as an IDE.
  - I then used Git add . to add my current changes to a workspace. 
  - I used git commit -m to commit said changes offically to my workspace. 
  - I used git push in order to push my changes to my Github Repository to update the offical copies of my code.
  - After my changes have been pushed :
  - In the GitHub repository, I navigate to the Settings tab 
  - From the source section drop-down menu, I select the Master Branch
  - Once the master branch has been selected, my page was automatically refreshed with a detailed ribbon display to indicate 
    the successful deployment. 

The live link can be found here - https://blaize-egelhof.github.io/Project_1/


## Credits 

In this section you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism. 

You can break the credits section up into Content and Media, depending on what you have included in your project. 
Media: 

-MEDIA:

Globally applicable images : 

Header background img URL :https://za.pinterest.com/pin/748653138049829887/ - Taken from https://pngtree.com/ With a huge thanks to the user 588ku who published this image from pngtree.com

Footer background img URL :https://za.pinterest.com/pin/748653138049829887/ - Taken from https://pngtree.com/ With a huge thanks to the user 588ku who published this image from pngtree.com

Index.html body : 
Landing page background img URL :https://slidescorner.com/backgrounds/background-for-tech-free-for-ppt-google-slides/ - Taken from https://slidescorner.com/ -Completly free to use.

Why choose us background section img URL :https://za.pinterest.com/pin/270356783867104506/ -Taken from https://www.istockphoto.com/vector/business-candle-stick-graph-chart-of-stock-market-investment-trading-financial-chart-gm921380008-253052413 -with credit to Istock publisher Yozayo . 

Meet-our-head-team section member img URL's: 
Profile 1: https://pixabay.com/photos/business-businessman-chair-computer-1839191/ - credit to Pexels 
Profile 2: https://za.pinterest.com/pin/193443746482722989/ -Published by @emilywongphoto , Full credit goes to @emilywongphoto. 
Profile 3: https://in.pinterest.com/pin/625437467023443753/ - Published under photodune.net  by vadymvdrobot , full credit to vadymvdrobot

Background img for Sign-up-form.html form and Login-form.html form: 
https://www.123rf.com/photo_19072901_abstract-futuristic-fade-computer-technology-business-background.html -Published by vska 

Meet-the-team.html body: 
background images : https://slidescorner.com/backgrounds/background-for-tech-free-for-ppt-google-slides/ - Taken from https://slidescorner.com/ -Completly free to use. , section below uses this exact image , but rotated 180degrees. 

Meet-the-team of investors img: https://za.pinterest.com/pin/1009580441445599246/ -Taken from fortunebuilders.com
under the Pinterest username:FortuneBuilders

Meet-the-team of AI Specialists img: https://za.pinterest.com/pin/330240585152398223/ -Taken from stocksy.com
under Pinterest username:Stocksy United 

### Content 

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos used on the home and sign up page are from This Open Source site
- The images used for the gallery page were taken from this other open source site


Congratulations on completing your Readme, you have made another big stride in the direction of being a developer! 

## Other General Project Advice

Below you will find a couple of extra tips that may be helpful when completing your project. Remember that each of these projects will become part of your final portfolio so it’s important to allow enough time to showcase your best work! 

- One of the most basic elements of keeping a healthy commit history is with the commit message. When getting started with your project, read through [this article](https://chris.beams.io/posts/git-commit/) by Chris Beams on How to Write  a Git Commit Message 
  - Make sure to keep the messages in the imperative mood 

- When naming the files in your project directory, make sure to consider meaningful naming of files, point to specific names and sections of content.
  - For example, instead of naming an image used ‘image1.png’ consider naming it ‘landing_page_img.png’. This will ensure that there are clear file paths kept. 

- Do some extra research on good and bad coding practices, there are a handful of useful articles to read, consider reviewing the following list when getting started:
  - [Writing Your Best Code](https://learn.shayhowe.com/html-css/writing-your-best-code/)
  - [HTML & CSS Coding Best Practices](https://medium.com/@inceptiondj.info/html-css-coding-best-practice-fadb9870a00f)
  - [Google HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html#General)

Getting started with your Portfolio Projects can be daunting, planning your project can make it a lot easier to tackle, take small steps to reach the final outcome and enjoy the process! 
