📝 **NOTE** Use this template to initialize the contents of a README.md file for your application. As you work on your assignment over the course of the week, update the required or stretch features lists to indicate which features you have completed by changing `[ ]` to `[x]`. (🚫 Remove this paragraph before submitting your assignment.)

## Week 1 Assignment: Flixster

Submitted by: **Marwan Kabir**

Estimated time spent: **10** hours spent in total

Deployed Application (optional): [Flixster Deployed Site](ADD_LINK_HERE)

### Application Features

#### Core Features

- [x] User can view a list of current movies from The Movie Database API as a grid view
  - The grid element should have an id of `movies-grid`
  - Each movie wrapper element should have a class of `movie-card`
- [x] For each movie displayed, user can see the following details:
  - Title - the element should have a class of `movie-title`
  - Image - the `img` element should have a class of `movie-poster`
  - Votes - the element should have a class of `movie-votes`
- [x] User can load more current movies by clicking a button at the bottom of the list
  - The button should have an id of `load-more-movies-btn`.
  - When clicked, the page should not refresh.
  - New movies should simply be added to the bottom
- [x] Allow users to search for movies and display them in a grid view
  - There should be a search input element with an id of `search-input`
  - Users should be able to type into the input
  - When a user hits 'Enter', it should send a search request to the movies API
  - The results from the search should be displayed on the page
  - There should be a close icon with an id of `close-search-btn` that exits the search, clears results, and shows the current movies displayed previously
- [x] Website accounts for basic HTML/CSS accessibility features
- [x] Website should be responsive

#### Stretch Features

- [ ] Deploy website using GitHub Pages.
- [ ] Allow user to view more details about a movie within a popup.
- [x] Improve the user experience through CSS & animation.
- [ ] Allow movie video trailers to be played using [embedded YouTube](https://support.google.com/youtube/answer/171780?hl=en)
- [x] Implement anything else that you can get done to improve the app functionality!
      (button transitions, dynamic search, CSS styling, Movie Clip Animation, Stock image of blank posterpaths, Placeholders in search, Button styling)

### Walkthrough Video

`TODO://` Add the embedded URL code to your animated app walkthrough below, `ADD_EMBEDDED_CODE_HERE`. Make sure the video or gif actually renders and animates when viewing this README. (🚫 Remove this paragraph after adding walkthrough video)

<div style="position: relative; padding-bottom: 55.46875%; height: 0;"><iframe src="https://www.loom.com/embed/cddcab8ee2e34df1b1bbadb0cc9f8bf0" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe></div>

### Reflection

- Did the topics discussed in your labs prepare you to complete the assignment? Be specific, which features in your weekly assignment did you feel unprepared to complete?

The labs that we were assigned did help complete the assignment. Lab 2 introduced us how to utilize the .document function
to create elements, classes, and utlize it to control objects actions. In Lab 3 we were introduced to using API's and taking in 
information, and creating functions that would display on a grid in the website. I would say the features that i felt unprepared for
was using "template strings". We weren't taught that in class, and it was something that was brought up around the end of class, and so
I went home to learn how to utlize it for the assignment, which helped me take in information from new pages, and my search funciton.
Another feature that I felt unprepared for was the CSS styling as its always been a struggle to understand the use cases for the different
formats we could use, we havent had an official lesson on flex box, so it was more testing than learning for that portion.

- If you had more time, what would you have done differently? Would you have added additional features? Changed the way your project responded to a particular event, etc.

If i had more time I would have added additional features onto my webpage. The features that I have are nice, but the user is really limited to what they can do, which is searching and loading in movies and I feel that if this is a movie app it should be able to pull information like trailers, information of the movie, and so much more. Although this is complex I feel like the final result would really encompass the fundamentals of HTML/CSS/JS. My search function intially responded with buttons, where i had to clear it to get default results, but I changed it so that I use an input event that makes the search more efficient and less tedious when it comes to clearing information and searching for what the user is looking for. Instead of clicking buttons I made it even simpler and added a placeholder for the user to understand what the search function is used for and the use of having no search button helps save the user time to find the movie that the want as a few key words or letters are enough to find the spesific movie vs submitting a whole title.

- Reflect on your project demo, what went well? Were there things that maybe didn't go as planned? Did you notice something that your peer did that you would like to try next time?

One feature that went well was my use of API's this is something that I was proud of because initially I was struggling to display data a few at a time because I was reading in the full page of data and displaying it at once, and to fix that I was able to do my own research on template strings and utilize them to create my fetchMovies and fetchSearchMovies function which is what makes the website so powerful. Another aspect that did not go as planned was the CSS styling because I'm still not familiar withe the use cases of some format properties and this led me to play around with a variety of function until I found the ones that fixed my formats. My peer incorporated a stretch/Access feature that utilized using alt-text for movies that were being displayed, and I would like to incorporate that in my next project because I'm starting to understand just how important accesibility features are important in the professional world and within big products.  

### Open-source libraries used

- https://lottiefiles.com/
I incorporated this to include an animation at the top of the page.
- https://serpstat.com/files/img/34/1676542462.4999.png 
This is a broken image picture that I made display whenever im reading in a movie that has no posterpath, so that users are able to see visually that the movie picture isn't available versus just having empty space. 

### Shout out

Throughout this whole week the people that have helped me come this far in my project and HTML/CSS/JS knowledge is Alan, Luis, Paige, Sammi, and Ashawn. I've been pair programming with Alan and Luis, which helped each of us come across problems that we ran into together and find solutions to later down the line. One of the best things about this dynamic is that each of us understand different aspects of the project and thats what helped us move so quick since each of us were comfortable with unique sections of the project and coming together helped us share what we know and what we didn't know. Paige and Sammi helped me understand my code conceptually and see what it is my function is really doing. Sammi helped me understand containers and how I formatted the containers of information that I would place within the grid. He also inspired me to work on a stretch feature that placed my own uniqe stock image url into the API path of movies that had no image withing their poster path. Paige helped me understand the two different fetch functions, and the difference between making Synchronous and Asynchronous functions, which was huge because the whole project was built on the sucession of me being able to pull in data to read. They also helped me solidify some terminology that helped me ask better and more spesific questions. 