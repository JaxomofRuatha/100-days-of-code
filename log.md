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
