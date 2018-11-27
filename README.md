# Milestone Project 1 for Fullstack Web Developer Course

This is a static web page that is for fans of 'The Monkees' band to view some of their previous (and future) work, along with being able to contact them in order to book an event


 
## UX

### Design

I went for a single scrolling page design, as while it meant that the initial load time might be slightly longer than if the site was split into multiple pages, the User would have full access to all the content.
From a coding perspective, it also makes it simpler to maintain, as a link would only need to be changed once, instead of having to be changed on multiple files.

For the general design (See the Design Documents Section), I went with a standard Header and Footer with a menu bar situated just below the header. Initially I did plan for a header image to appear at the top of the page, but after reviewing the planned image ('assets/images/monkees.jpg'),this would not fit with the view that I had.

Considering that the main target of this website is for fans, A static header and footer seemed to be the best method, particulaly since there was a permanent link to the booking form in the footer. 

The color scheme was generated using a w3 schools tool (See the **Tools** Section)
### User Stories

- As a event organiser, I want to book them for my event, so that I can then state that they would be playing live on the night.
- As a new fan of the band, I want to find out some of the history about the band
- As a longtime fan, I want to listen to some of their tracks and music video(s)



### Design Documents

- Initial Design document(s), including a font test to preview what the fonts would look like are available from the 'designs' folder


## Features

### Existing Features

#### Navigation
- Each of the menu links takes the user to a specific part of the page, since there is no extra pages to load.

#### Interactivity
- Song Lyrics - By Users clicking on the 'Lyrics' below each song, a dropdown appears that contains each of the lyrics for the song.


### Features Left to Implement

#### Content

##### Proper biographies for each band member, instead of their date of births

This links in with the dropdown's below, as each members biography was a different height, it was hard to get a common height that would make them appear correctly, javascript would again have been able to fix this, this height could have also been set to the tallest element's height.

#### Equal Height for dropdowns
    
At the moment, the dropdown height's when expanded are all different , this is due to the differing number of words in each lyrics.

If I had been able to use javascript/JQuery, these could have been made a dynamic height that is based off of the tallest element.

#### Form Functionality

At the moment the contact form does not do anything, with the addition of a backend system, this could be made to send an email, and return a confirmation message to the user, confirming that the email has been sent. 
        

## Technologies Used

In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.
- [HTML5](https://www.w3.org/standards/webdesign/htmlcss)
    - **HTML5** is the basic building language of all websites, it allows for structure 
- [CSS3](https://www.w3.org/standards/webdesign/htmlcss#whatcss)
    - **CSS 3** is used to describe web pages, via color, font and other styling. In the project it is used for styling the elements on the page 
- [Google Fonts](https://fonts.google.com/)
    - The project uses the 'Lobster' and 'Roboto' fonts which are available from this font repository for free use.
- [JQuery](https://jquery.com)
    - The project uses **JQuery** to simplify DOM manipulation.
- [Bootstrap v3.3](https://getbootstrap.com/docs/3.3/)
    - The project uses **Bootstrap** for the navbar functionality, along with making the images responsive and responsive visibility classes. In addtion it provides the 'grid' functionality for layout purposes.

### Tools

- [W3 Schools Color Scheme - Triadic](https://www.w3schools.com/colors/colors_triadic.asp)
    - I used this tool to help me create a color scheme for use in the site.
- [Markdown Table Generator](https://www.tablesgenerator.com/markdown_tables#)
    - Used to generate the table in the 'testing' part of this readme.
    
## Testing





| Test Number 	| Section of the site 	| What Should Happen 	| What Actually Happened 	| Actions to Take (If Any) 	|
|-------------	|---------------------	|--------------------	|------------------------	|--------------------------	|
| 1           	|                     	|                    	|                        	|                          	|
| 2           	|                     	|                    	|                        	|                          	|
| 3           	|                     	|                    	|                        	|                          	|
| 4           	|                     	|                    	|                        	|                          	|
| 5           	|                     	|                    	|                        	|                          	|
| 6           	|                     	|                    	|                        	|                          	|
| 7           	|                     	|                    	|                        	|                          	|
| 8           	|                     	|                    	|                        	|                          	|
| 9           	|                     	|                    	|                        	|                          	|
| 10          	|                     	|                    	|                        	|                          	|
| 11          	|                     	|                    	|                        	|                          	|
| 12          	|                     	|                    	|                        	|                          	|
| 13          	|                     	|                    	|                        	|                          	|
| 14          	|                     	|                    	|                        	|                          	|
| 15          	|                     	|                    	|                        	|                          	|
| 16          	|                     	|                    	|                        	|                          	|


## Deployment

### Github Deployment 

The site is available to view via [here](https://lowe54.github.io/milestone1_project/)

The following steps were made in order to deploy
- In a terminal, the git repository was initiated via the `git init` command
- The repository was linked to a .git file on github via
    - `git remote add origin https://github.com/Lowe54/milestone1_project.git`
    - `git push -u origin master`
    
- After each change, the following commands were used to push the changes to the git repository
    - `git add *` - This adds all changed files to staging
    - `git commit -m "MESSAGE HERE"` - Commits the work with a brief message as to what has changed
    - `git push` - This pushes the work to the git repository, after entering your github username and password


### Github Cloning
- In order to clone the github repository, type the following command in a terminal
    - `git clone https://github.com/Lowe54/milestone1_project`
- If you wish to change the default directory to where the project is checked out to, use the following command 
    - `git clone https://github.com/Lowe54/milestone1_project *FolderName*`

## Credits

### Content
- Lyrics obtained from
    - [Last train to clarksville](https://www.azlyrics.com/lyrics/monkees/lasttraintoclarksville.html) - https://www.azlyrics.com/lyrics/monkees/lasttraintoclarksville.html
    - [Daydream believer](https://www.azlyrics.com/lyrics/monkees/daydreambeliever.html) - https://www.azlyrics.com/lyrics/monkees/daydreambeliever.html
    - [I'm a believer](https://www.azlyrics.com/lyrics/monkees/imabeliever.html) - https://www.azlyrics.com/lyrics/monkees/imabeliever.html
    - [I'm not your stepping stone](https://www.azlyrics.com/lyrics/monkees/imnotyoursteppinstone.html) - https://www.azlyrics.com/lyrics/monkees/imnotyoursteppinstone.html

- Band Information (About Us Section) obtained from the following:
   - [General Band Information](https://en.wikipedia.org/wiki/The_Monkees) - https://en.wikipedia.org/wiki/The_Monkees
   - [Peter Tork](https://en.wikipedia.org/wiki/Peter_Tork) - https://en.wikipedia.org/wiki/Peter_Tork
   - [Davy Jones](https://en.wikipedia.org/wiki/Davy_Jones_(musician)) -https://en.wikipedia.org/wiki/Davy_Jones_(musician)
   - [Michael Nesmith](https://en.wikipedia.org/wiki/Michael_Nesmith) - https://en.wikipedia.org/wiki/Michael_Nesmith
   - [Micky Dolenz](https://en.wikipedia.org/wiki/Micky_Dolenz) - https://en.wikipedia.org/wiki/Micky_Dolenz

### Media
- The photos, video and audio used in this site were obtained from https://github.com/Code-Institute-Org/project-assets/tree/master/stream-1/band-assets

### Acknowledgements
