# Agency-Website
Practice in making an agency website for the FAC Markup using HTML, CSS and Raw Javascript.

The project aims to create a modern, responsive and user-friendly website that showcases our agency

- [Components](#Website-Components)
- [Extra notes](#Extra-Notes)
- [Dev Log](#Development-Log)
## Website Components

### UI Elements
- Navigation bar
    - need to decide on a style/ functionality of navbar we want 
- Landing page banner
    - not sure what how we want it to look yet
    - A welcoming landing page introducing our agency and its core values.
- About us section
- Meet our team section
    - use grid to display the cards
    - a tile or a card for each memeber
        - image
        - name
        - short bio
- Contact us section
    - a forms element

### JS Elements
- Nav bar scrollspy?

### Responsive and Accesibility Considerations
- need to ensure website can accomodate mobiles screens
- Screen readers needed for website accesbility


## Theme ideas
- photograpgy agency
- game coaching company?
- private investigators?
- personal assistant?
- careers coaching/advice?
### Sketch Create pitch
**Sketchy Business Creations: Where Doodles Meet Deadlines!**

(about us)
Celebrate the creative chaos of ideation and design. Use doodles, sketches, and playful illustrations to send us a commission of what want us to make here at SBC. We are commitmitted to turning imaginative ideas into tangible results using pure magic!

Our dedicated team of experinced ~~con~~ artists, will be able to reliably  dicipher and envision your fantastic idea. Once passed on to our schemers they'll work with our psudo-professional production team to quickly tirelessly conjure up your commission!

(small text) SBC.inc will only accept contracts in full prepayment using crypto, all contract will be fufilled within 1 month but is not obligated to update client on the progess during fulfilment.

(refferal to forms) We are more than happy to quote on your commission so feel free to contact one of our ~~scamm-~~ sales reps with the following form and our ~~frauds~~ financial team can draw up ~~hustle~~ holistic plan to bamboozle you with!

## Features to be considered

1. Theme changer
2. Glassmorphism aesthetic
3. Moving text banner


# Extra Notes

## View a branch when reviewing a pull request
- to view a remote branch from someone else you must
    - git fetch -p
    - check to that branch
        - you should checking the github repo and seeing what pull requests there are in relation to what branch you want to be checking
        - if you need help finding the branch use:  git branch -a
        - **** if the list of branches are getting to long and hard to find the right one use: git fetch -p, then try again with git branch -a
    - If you approve of the pull request changes, accept the pull request on github to merge to main
        - remember to delete the branch on github
## Post pull request
- after accepting pull request you must
    - update your main on local
        - check to main
        - pull
    - merge main to your local working branch (local meaning your vscode)
        - check to your working branch
        - merge main
    - **there will be a merge conflict**, resolve the merge conflict in vscode with the conflict editor (there is a button)
        - if we want everything, accept both, otherwise use judgement of what which one needs to be implemented
    - you may need to git commit after merge to conclude it
    - after merge, remember to push your local working branch to github
        - git push
This will allow to work on your current feature but ensure it's uptodate with main
## When you have done some code you want to add to main
- make sure you have added, committed and pushed everything in vscode
- on github make a pull request for your branch

# Development Log
## Contact Form
### 0.2
- Added a test environment for the forms element
- added CSS to fit the themeing and present a good layout
- CSS adjusted to fit on mobile
- I think i need to look into screen reader functionailty on the form
- added max length to limit data sent to server
### 0.1
- added basic contact form components
- needing CSS
> Jack L

## Team Cards
### 0.2
- ~~made some CSS standardisations regarding font size and REM~~
- component scrapped

### 0.1
- did a large scale reformat of the CSS and structured it in a top down order
- added the html elements for the team section
    - the grid box
    - cards with placeholder image and text
- added and adjusted CSS to have grid implemented to position the cards nicely
    - current format has poor responsiveness and does not adjust well to varying screen sizes
- added flex and adjusted grid to position the elements within the team to have nice proportions and look neat
> Jack L

# needs to be done
- Client wants to be able to see information about each member of team so that I can know who they are.
    - make cards - done
    - picutres of each memebr fit nicely on card
    - name
    - bio needs to be written
    - All the business 
- navigation
    - Website needs a good navigation menu or bar to fulfil the acceptance criteria - **done**
    - Clients will want to be able to click to navigate to different sections of webpage - **done**
    - For accessibility enable clients to be able navigate website using keyboard controls
- contact form
    - good labels and a11y tags
    - correct types
    - required tags
    - responsive size