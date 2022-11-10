# landing-page
A landing page to practice front end web design

10/11/2022 - Today was really good. I felt like I knew exactly how to accomplish what I was setting out to do and when I needed to look something up my suspicions of what the solution I was looking for were correct. I feel like I'm starting to get the hang of this and it's a big relief. 

09/11/2022 - I added text bellow the thumbnail boxes. For alignment purposes I needed to put both the text divs and the box divs into another parent div so they stocked on top of each other nicely.

08/11/2022 - I'm getting very close to finishing and it is finally feeling like it's coming along. I need to import some custom made buttons but besides that I feel like I won't have any further issues.

08/11/2022 - I don't want my CSS to look like a grocery list anymore and I suspect SASS will help with that. I should put some time into learning SASS just to understand what it is and how it's applied.

07/11/2022 - Sick today but I wanted to keep the habit of coding going. I placed row2 and row3 down. I feel like having a standardized cell naming system would be good for the future. Placing the div by grid then using flex to manipulate things within it is working great right now. I'm really happy with it so far.

06/11/2022 - The first two rows are now done and I'm very happy with them. The next row looks like it doesn't need the two center columns but a single center column with everything aligned to center. Also, I should finish reading this: https://css-tricks.com/auto-sizing-columns-css-grid-auto-fill-vs-auto-fit/ because I need to understand this a bit better. I'm not sure if updating the first line of my stylesheet with a * instead of body made a difference but suddenly the website worked the way I expected it to. It makes me think that when I refresh the page it doesn't always pull the new information.

04/11/2022 - the divs for margins works and adding flex display for child divs was working pretty good except that when I make the flex direction into columns it seems to ignore the justify-content: right attribute. When I inspect the <p> tag I can see that it defaulted back to a block display but I'm not sure why.

04/11/2022 - I realized I could make divs for the margins and give a second class for each tag in the same row so that I could target all of them with background-color. It worked but justify-items would make it so the color would only paint the element and not the entire grid area.

03/11/2022 - I had to use the command "git checkout -b [branch name]" to change my push direction... I guess that's how you refer to it... It worked and I'm happy lol.

03/11/2022 - I made a branch but now I'm confused... I guess I just push my experimental stuff to my new branch. Though, I don't quite understand the command "git push origin main". I need to know what "origin" means in that context.

03/11/2022 - I want to try making a different layout. I have been fooling around with grid display but now I think I should come back to flexbox. To do this initially, I tried making copies of the index and style sheet but I now know that I should make branches in git. I'll try making a branch today to work on this new idea. It looks like I have already made a mess with my experimentation but this skill will probably lead to more thorough exploration and documentation. The one thing I wonder about is keeping the README for the main branch so when I update a new branch with README entries it is consistent.

02/11/2022 - Grid is confusing but I think I'm getting it. I think I will try grids within grids next time. Lay out a grid of just the rows so that I can target the background-color of each row. Then make grids within each row to custom fit where I want the elements to sit within each row. Also, I should mention that I came across an article saying that grid should be used with flexbox, not replace it. I'll have to learn flexbox better.

01/11/2022 - I started from scratch because I realized I was thinking about this all wrong. I don't need as many divs as I thought it did and I don't need parent divs.

31/10/2022 - I'm over it for now though I think I need to give a div to each grid cell so I can associate it ith a class if need be. Seems like they did that in this link: https://www.w3schools.com/css/tryit.asp?filename=trycss_template2_grid

31/10/2022 - I'm lazy today and a bit annoyed so I want to get my ideas out before starting. I think I want to be able to lay the structure and the basic text size/weight out before even filling the page. It only makes sense to me if you are using this style sheet for multiple pages to lay it out before anything else and then fill in the blanks. Step one will be to lay out the basic grid and somehow attach boxes to that parent grid. From there I want to have grids within the parent grid but I feel like this is where things fall apart. Lastly (kinda) I want the child grids to never break the parent grids boarders. Oh, and I want the boxes to grow to fit the element. I have text spilling over at this point. Ok, last last comment: I feel like I should have some default colours that I use when laying everything out to, 1. create visual separation and 2. show me what I still need to work on.

28/20/2022 - I realized that having a basic structure that everything lives within is probably the best way to go about this. I started a second style sheet to see if I can figure this out starting from the bottom but it isn't going so well. I'm going to work on creating a grid that everything lives in first and from there build boxes within that.

27/10/2022 - The objects within column a and b are suppose to be aligned to the left and right and when I noticed I had already started committing to what I was doing. I see now that it's annoying to not do it like that but I'm to lazy to change it. Also, I don't know why the text in the image section isn't aligning to true center. Lastly, when changing the size of the window, the boxes will breach their parent boxes.

25/10/2022 - I placed the text into section 1 but it's not fitting itself into the box. It is forcing itself out of the div and I need to look up how to make the box flex or the text shrink... Probably the box stretch but I should reduce the size and weight of the font too.

24/10/2022 - Before I forget, I used Lorem Ipsum in my code today to generate placeholder text and it's fucking cool. I finally feel like I'm getting somewhere with this stuff. Learning the structure has made me feel like I am actually doing something. It's probably because you can see the results after making it. Well... It also feels like you should build the structure of a house before you put the plumbing and wiring in.

23/10/2022 - I started over with the CSS structure. After watching a beginners guide for grid I have a better understanding on what I need to do. It actually feels really good and I think this will go much faster if I exclusively use grid instead of grid and flexbox combined.

21/10/2022 - I tried using the grid display but I'm getting an error that makes it seem the browser doesn't even recognize the code. I know it understands 'display:grid' but it didn't like the grid structure I made.

19/10/2022 - I added a grid property to the links class and I'm not quite sure how it works but I'm happy with the alignment. I will need to understand how the "grid-template-areas" property works because it seems powerful but I'm not exactly sure what it does. There seems to be a default spacing assigned with it and I'm assuming it is breaking the links div into 3 equal parts.

16/10/2022 - Happy with the boxes and now I'm fooling around with adding content to each box. Seems somewhat straight forward so far but I'm assuming I'm going to have difficulties with the 3 images.

15/10/2022 - Getting stuck with making the flexbox fill space. I'm not sure how to equally distribute them or even if I should. I'm also not sure how I make a child element fill the parent element.