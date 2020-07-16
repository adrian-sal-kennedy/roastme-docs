# Roastme!

A social cookbook. Perhaps a social library of social cookbooks.

Users can create a recipe using an intuitive tool set, refine it as it evolves, and ultimately publish and share it in an attractive blog format designed for sharing on your favourite social media platforms.

The ultimate goal is a sort of github for recipes. Each recipe maintains a complete history of every change made, and which user made that change. Users can "fork 🍴" a recipe and it becomes theirs, free to modify as they please.

## Purpose

Cuisine is arguably the only thing all the myriad cultures and creeds in this world can agree on and bond over.

Recipes have deep roots in culture, as reflected in the huge swaths of text one finds when they look up any recipe ("skip to ingredients" please).

Probably because of this, the best dishes don't have well-defined recipes with uniform or even repeatable measures for what needs to go on or in them. Many include whimsical measures like drams, handfuls or cups.

Initially Roastme will simply define recipes in text, however under the hood there will be room to get all of this into grams, taking into account the densities of different ingredients that would otherwise be measured by volume.

We are [actively][1] [researching][2] [ways][3] users might want to interact with online recipes, and as a stretch goal we are looking into IoT integration - recipes are stored as structured data so connecting our api to other frontends is just a matter of correct formatting.

[1]: https://developers.google.com/search/docs/data-types/recipe
[2]: https://api2.bigoven.com/web/documentation/recipes
[3]: https://www.amazon.com.au/newscorp-Taste-com-au/dp/B0778JD3H2

## Functionality / features

### MVP features

- Mobile first
- Faves - like recipe bookmarks
- Image uploading / Amazon S3
- Heroku / Netlify deployment
- User rating
- Search / filtering / sorting
- Unit conversion (internally all grams)
- Scale by number of servings
- Comments threads on recipes

### Aspirational features

- Track recipe history
- "Clone" recipes, conceptually similar to git
- Data captured on unique views
- Trends
- Recommended recipes

## Target audience

Any home cook who is looking for new and exciting recipes, or looking for a springboard to develop their own unique takes on them.  
A particular focus on food bloggers, instagrammers and even food businesses looking to promote themselves through social media.

## Tech stack

Ruby on Rails  
Javascript - React  
HTML/CSS  
Amazon S3  
Heroku  
Netlify

## Dataflow diagram

![Dataflow diagram](./docs/DataflowDiagram.png)

## Application Architecture Diagram

![Application Architecture Diagram](./docs/ArchitectureDiagram.png)

## User stories

## Wireframes

![Mobile UI - first 4 views](./docs/wireframe-01-04.png)
![Mobile UI - second 4 views](./docs/wireframe-05-08.png)
![Mobile UI - last 3 views](./docs/wireframe-09-11.png)
![Desktop UI - first 2 views](./docs/wireframe-2-01-02.png)
![Desktop UI - second 2 views](./docs/wireframe-2-03-04.png)
![Desktop UI - third 2 views](./docs/wireframe-2-05-06.png)
![Desktop UI - first 2 views](./docs/wireframe-2-07-08.png)
![Desktop UI - last 2 views](./docs/wireframe-2-09-10.png)  

## Trello management
