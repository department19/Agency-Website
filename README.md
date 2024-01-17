# Agency-Website
Practice in making an agency website for the FAC Markup using HTML, CSS and Raw Javascript.
<br>
The project aims to create a modern, responsive and user-friendly website that showcases our agency
<br>
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

## Theme ideas
- photograpgy agency
- game coaching company?
- private investigators?
- personal assistant?
- careers coaching/advice?

## Features to be considered

1. Theme changer
2. Glassmorphism aesthetic
3. Moving text banner


## Responsive and Accesibility Considerations
- need to ensure website can accomodate mobiles screens
- Screen readers needed for website accesbility



# Extra Notes

- to view a remote branch from someone else you must
    - git fetch
    - check to that branch
        - if you need help finding the branch use:  git branch -a
        - **** if the list of branches are getting to long and hard to find the right one use: git fetch -p, then try again with git branch -a
- after accepting pull request you must
    - update you main
        - check to main
        - pull
    - merge main to working branch
    - remember to push to your remote branch after

# Development Log
## Team Cards
### 0.1
- did a large scale reformat of the CSS and structured it in a top down order
- added the html elements for the team section
    - the grid box
    - cards with placeholder image and text
- added and adjusted CSS to have grid implemented to position the cards nicely
    - current format has poor responsiveness and does not adjust well to varying screen sizes
- added flex and adjusted grid to position the elements within the team to have nice proportions and look neat
> Jack L
