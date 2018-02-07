# 100 Days Of Code - Log

### Day 0: January 1, 2018

**Today's Progress**: Worked on getting Portfolio to use updated build process and packages, reorganized file structure.

**Thoughts:** Unfortunately most of the evening ended up being spent on trying to fix the development environment with my Ubuntu VMWare machine and dealing with a VS Code issue crashing my attempts at progress with npm. Successfully got Pug and Sass working with npm scripts though!

### Day 0.1: January 7, 2018

**Today's Progress**: Finalized initial Portfolio development environment and some tweaks, revisited Weather build.

**Thoughts:** I changed over from a Gulp build process using multiple server instances for development to a single one using BrowserSync and npm scripts, in addition to separating out the scripts for production build. Had some issues with Chrome/Firefox displaying UI differently, unable to fix initially but consistent scaling needs to be addressed in several applications. I went back to the Local Weather application and updated the packages and a few scripts.

**Link to work**: [Portfolio](https://github.com/JaxomofRuatha/Portfolio)

### Day 1: January 8, 2018

**Today's Progress**: Modified landing page and autocomplete UI for Local Weather application

**Thoughts:** Having some issues with the autocomplete form's styling, but the functionality is restored and I was able to get a better feel for how the third party React component is set up.

**Link to work**: [JOR Local Weather](https://github.com/JaxomofRuatha/fcc-weather)

### Day 2: January 9, 2018

**Today's Progress**: Committed the shell for React/Redux opinionated boilerplate, played around with sandbox settings, touched up Weather a bit more.

**Thoughts:** Today was my last day at my job due to contract termination, so...actually happy with how much I got done, even if most of it wasn't coding. I've been meaning to get some personal templates/starters set up for a while, especially for experimentation, so this is a good step in that direction!

**Link to work**: [JOR React/Redux Starter](https://github.com/JaxomofRuatha/jor-react-redux-starter)

### Day 3: January 10, 2018

**Today's Progress**: Worked out a pretty significant portion of how I want to have my boilerplate set up, including file structure

**Thoughts:** I'm going to be setting things up from the starter to use in my Recipe Book application (which will end up being a more full-fledged health app eventually). For now things are placeholders, but I am creating a layout for what I want to be the baseline starter kit elements versus the more specific portions (Sequelize vs Mongoose vs No ORM MongoDb/MySQL/PostgreSQL, etc.)

**Link to work**: [JOR React/Redux Starter](https://github.com/JaxomofRuatha/jor-react-redux-starter)

### Day 4: January 11, 2018

**Today's Progress**: Mostly worked on the edx course for Simple Data today (using Racket) along with continuing to tweak development environments.

**Thoughts:** I'm debating whether I want to stick with using WSL, and/or trying to determine whether there's an effective way to get GUI programs to launch correctly from the WSL Bash/Fish prompt. I have Docker working in Toolbox at least, but I haven't tried integrating it with the normal commands within the Bash terminal. I may end up giving up on convenience and dual-booting Linux rather than trying to emulate it...

### Day 5: January 12, 2018

**Today's Progress**: Continuing to modify boilerplate, spent several hours helping with another student's project setup and Instagram API

**Thoughts:** I'm starting to thing more and more that I really like the DevOps part of programming. All the cool automation tools get me super excited, and I find myself getting sidetracked into build process and environment setup all the time. Just another facet of things that make me wonder why I didn't decide to go this route earlier!

### Day 6: January 13, 2018

**Today's Progress**: Continued on several things (boilerplate, Docker, Racket, Wordpress, API things, Wikiviewer), mostly ended up learning a lot more than I planned about Bash/Linux advanced usage.

**Thoughts:** I made the mistake of trying to upgrade WSL to Ubuntu 17.10, and between that breaking everything and Fish continuing to lag things out, I reinstalled and switched to ZSH. Pretty happy with it so far, and in the process I learned a ton about Bash setup. Also realized today that I can have a server running Wordpress without actually hosting said server. Obvious but somehow it didn't click until the meetup today.

### Day 7: January 14, 2018

**Today's Progress**: Started on the Calculator project (probably going to use Typescript, possibly Angular), able to get the Wikiviewer compiling and sending AJAX requests again.

**Thoughts:** In keeping with trying to use varied technologies between projects, I learned most of TypeScript basics today and started using it for my Calculator app. So far it's very basic, but I'm likely going to use the project to learn Angular. I was able to finally clean up my Frankenstein code with the WikiViewer (I had tried to implement too many new things at once), so at least it's back to compiling without errors.

**Link to work**: [JOR WikiViewer](https://github.com/JaxomofRuatha/fcc-wikiviewer)

### Day 8: January 15, 2018

**Today's Progress**: Continued modifying boilerplate, mostly worked on WikiViewer

**Thoughts:** I spent a good portion of today figuring out how to make Redux play nice with Immutable and structure things appropriately. I have better access to what's happening now, but still running into some issues.

**Link to work**: [JOR WikiViewer](https://github.com/JaxomofRuatha/fcc-wikiviewer)

### Day 9: January 16, 2018

**Today's Progress**: WikiViewer almost ready to have React UI implemented.

**Thoughts:** I finally got to a structure I'm pretty happy with for my WikiViewer, and now the only things remaining are the UI and getting Redux Saga to behave. Unfortunately I ended up banging my head against (what I'm assuming is) async yet again, as my Saga is returning `undefined` even when everything indicates the data is correctly retrieved and processed.

**Link to work**: [JOR WikiViewer](https://github.com/JaxomofRuatha/fcc-wikiviewer)

### Day 10: January 17, 2018

**Today's Progress**: Worked on getting docker-compose to work on two different environments

**Thoughts:** Kind of an off day, had to help a friend and apparently Docker doesn't like either of my computers very much.

### Day 11: January 18, 2018

**Today's Progress**: Still having some issues with WikiViewer and redux-saga

**Thoughts:** I ended up going to a meetup that happened to be on the topic of redux-saga, got some ideas where to try and fix things but still unable to completely get working before the end of the day.

**Link to work**: [JOR WikiViewer](https://github.com/JaxomofRuatha/fcc-wikiviewer)

### Day 12: January 19, 2018

**Today's Progress**: WikiViewer redux-saga finally working, added in data transformation from API.

**Thoughts:** Continuing to work through the various layers of React/Redux/Immutable libraries I decided to implement on this project. I'm pretty happy that I learned them on something relatively straightforward, because some of the documentation is not clear at all (especially for my use case of "everything working together and Immutable.js data structures").

**Link to work**: [JOR WikiViewer](https://github.com/JaxomofRuatha/fcc-wikiviewer)

### Day 13: January 20, 2018

**Today's Progress**: WikiViewer reducers and data flow updated, crude selector set up and working.

**Thoughts:** Some of the original and continuing issues I've been having on this project were due to libraries not taking Immutable into account (shocking), so I fixed those parts. Still trying to fully implement normalizr and reselect, since their documentation and examples are the least useful by far for what I'm trying to do with them.

**Link to work**: [JOR WikiViewer](https://github.com/JaxomofRuatha/fcc-wikiviewer)

### Day 14: January 21, 2018

**Today's Progress**: Worked on getting the image search microservice updated, continued cleaning up Portfolio.

**Thoughts:** I at least was able to figure out the API for the image search and set up the architecture to what I've started to use more. I haven't quite had a chance to finish updating every file, but it should be pretty quick as soon as I go back through.

**Link to work**: [Image Search Microservice](https://github.com/JaxomofRuatha/fcc-imagesearch)

### Day 15: January 22, 2018

**Today's Progress**: I started on a front end boilerplate that allows me to do something similar to Codepen with testing out designs.

**Thoughts:** I've wanted to start working more on truly front end since I've done far more either back-end or non-visual front end data. I'm already excited about the starter I'm making for my full-stack React, but this is going to be much more of a sandbox to just experiment with.

**Link to work**: [Design Playground](https://github.com/JaxomofRuatha/design-playground)

### Day 16: January 23, 2018

**Today's Progress**: Started on testing for WikiViewer since I got out of it some with the documentation issues in the technologies working together.

**Thoughts:** I was able to get a few tests running but partway through I figured out part of the problems I was having with reselect and started on sorting those out. Still having difficulties, and as much as Immutable is part of the problem, I think I want to work on some documentation for these libraries so people don't have the same issues.

**Link to work**: [JOR WikiViewer](https://github.com/JaxomofRuatha/fcc-wikiviewer)

### Day 17: January 24, 2018

**Today's Progress**: Revamped naming system on Portfolio and cleaning up SCSS to match better practices.

**Thoughts:** I've been putting off completely cleaning up all the CSS for my Portfolio, since it's been through various iterations where Grid was partially implemented and also where I was testing various front end tools. Now at least the naming conventions and structure are more maintainable, and getting better!

**Link to work**: [Portfolio](https://github.com/JaxomofRuatha/Portfolio)

### Day 18: January 25, 2018

**Today's Progress**: I dabbled in several projects today (Portfolio, Wiki, starters) and watched the rest of the CSS Grid course.

**Thoughts:** Not as much time today, but able to make some progress on several projects and mostly learning.

### Day 19: January 26, 2018

**Today's Progress**: Continued to make progress in untangling the Portfolio CSS and making the Wiki Redux libraries work.

**Thoughts:** I dealt with some computer issues today, but was still able to get a decent amount done on both projects. Mostly at this point the issue with Wiki is figuring out exactly what each library is doing with the data it's getting, and what it's giving to the next library in line to process.

**Link to work**: [Portfolio](https://github.com/JaxomofRuatha/Portfolio), [JOR WikiViewer](https://github.com/JaxomofRuatha/fcc-wikiviewer)

### Day 20: January 27, 2018

**Today's Progress**: Rebuilt most of the Portfolio to actually take advantage of CSS Grid

**Thoughts:** Now that I'm a little more comfortable with it, I'm using CSS Grid for almost every part of my page. Initially I had avoided it entirely because I was concerned about compatibility, and later I only used it when there were more complicated components that needed advanced layout tools, but I'm working to replace most if not all of the flexbox in the project and have it work out to be responsive as a side effect in many cases.

**Link to work**: [Portfolio](https://github.com/JaxomofRuatha/Portfolio)

### Day 21: January 28, 2018

**Today's Progress**: Updated the layout of the Projects section.

**Thoughts:** I changed the Projects viewer to look a bit cleaner after getting feedback on what it looked like. I'm not sure on some of the coloring and likely will change some of it later, but it's looking considerably less clunky.

**Link to work**: [Portfolio](https://github.com/JaxomofRuatha/Portfolio)

### Day 22: January 29, 2018

**Today's Progress**: Worked on some of the MOOC.fi Java course, got Docker working on W10 mostly.

**Thoughts:** I'm going back to working in Java some, since I feel like I'm well-versed enough in the JS ecosystem now to branch back out a bit. I think it helps a lot with seeing different "best practices" and applying them to what I've been doing in other frameworks. I also spent a while trying to get Docker working in WSL, and though it's still kind of clunky I at least have it able to SSL connect through and access it as normal. I'm considering getting W10 Pro just for Hyper-V since that seems to be the root of a lot of my issues...

### Day 23: January 30, 2018

**Today's Progress**: Got tab functionality working again for portfolio Projects.

**Thoughts:** I was able to get the updated layout working correctly with the tabs event listeners, though still having some issues with it being inconsistent.

**Link to work**: [Portfolio](https://github.com/JaxomofRuatha/Portfolio)

### Day 24: January 31, 2018

**Today's Progress**: Restructured HTML to reflect semantic guidelines as much as possible, eliminated some nesting.

**Thoughts:** Now that I have a better idea where I want the finished version of this project to be, I updated the tags to be more in line with expectations for HTML5 semantics. I also moved some things around to have them work better with the CSS/layout/interactions since the original versions hadn't been planned out with the current structure in mind.

**Link to work**: [Portfolio](https://github.com/JaxomofRuatha/Portfolio)

### Day 25: February 1, 2018

**Today's Progress**: Fixed errors with clickable regions on portfolio.

**Thoughts:** I figured out what the issue I was having with the tabs was: the anchor tags weren't taking up the entirety of the list elements, so when I clicked outside the covered area the variables weren't being stored correctly as targets. Everything is working as intended now, though I will be adding in error handling to make sure that doesn't happen in other unexpected ways.

**Link to work**: [Portfolio](https://github.com/JaxomofRuatha/Portfolio)

### Day 26: February 2, 2018

**Today's Progress**: Added content for Project section, cleaning up other styling.

**Thoughts:** Now that the section for projects is working correctly, I added and updated some of the content to each. This included finding out that Firefox Developer Edition has a sweet screenshot function included, which just makes me love it even more than I already did!

**Link to work**: [Portfolio](https://github.com/JaxomofRuatha/Portfolio)

### Day 27: February 3, 2018

**Today's Progress**: Worked more on the Java course, started going through and updating files.

**Thoughts:** Not a lot of true coding done today, but I am hoping to start on getting some writing done for the technology/tutorial blog I've been planning for a long time. With the meetups I've been leading, I've realized how much of a need there is for a better structuring of learning for those between beginner and advanced.

### Day 28: February 4, 2018

**Today's Progress**: Fixed issues on portfolio with external link layering, updated the format of Contact section, trying to get PostCSS working and live version correctly running.

**Thoughts:** Unfortunately the documentation for PostCSS in a non-Gulp environment isn't terribly good, and I've run into some issues with getting it to play nice with the node-sass compiler process I already have running. I was able to get a dedicated branch set up for the production build, so it's at least live, but it certainly still needs a lot of work.

**Link to work**: [Portfolio](https://github.com/JaxomofRuatha/Portfolio)

### Day 29: February 5, 2018

**Today's Progress**: Finished both the Image Search and File Metadata Express microservices (not styled yet).

**Thoughts:** The image search API went pretty smoothly after I stopped trying to use Google's custom search API (since it has pretty significant limitations without paying) and switched to Pixabay. The metadata project was extremely simple and only took a couple hours to complete in its entirety, since I already had a basic structure set up from other projects.

**Link to work**: [JOR Image Search](https://github.com/JaxomofRuatha/fcc-imagesearch), [JOR Metadata](https://github.com/JaxomofRuatha/fcc-metadata)

### Day 30: February 6, 2018

**Today's Progress**: Completed the WikiViewer (minus some bugs and cleanup), finished two intermediate algorithm problems, set up a hub for the Express microservices

**Thoughts:** Extremely productive day! I couldn't sleep for a while the night before, and ended up solving the problem I was having with the data displaying incorrectly with React because of Immutable objects. From there I was able to completely set up the UI and style everything, and it's working completely. There are a few snags with using the images and cleaning up some of the code that I wasn't certain how to handle initially, but at this point it's just polishing.

And for the hub, I was considering making an actual site, but I think it works out nicely to just have a markdown file with the links. I may change my mind on that later, but for now I think it works well as a starting point given how basic the projects are UI-wise.

**Link to work**: [JOR WikiViewer](https://github.com/JaxomofRuatha/fcc-wikiviewer), [Microservices Hub](https://github.com/JaxomofRuatha/microservices-hub), [Algorithm Practice](https://github.com/JaxomofRuatha/Algorithm-Practice)
