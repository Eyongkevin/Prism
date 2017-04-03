# Prism

### Minimum Viable Product
Prism will be a Chrome extension that allows a user to filter a web page using 1 of 8 different filters. These filters are designed to simulate different types of color-blindness, allowing the user to view a website through the eyes of a color-blind user. Developers, for example, can utilize the extension to engineer their site’s UI/UX.

- [ ] Chrome extension
- [ ] 8 filters to use
- [ ] Clears a filter
- [ ] Changes photos and text
- [ ] Options to just do text/just photos/whole site
- [ ] Material Design


### Wireframe
![wire-frame](./docs/wireframe/prism_wireframe.png)

### Technologies
Our Chrome extension will be implemented using: jQuery, HTML, and CSS. We will have one script fill that has the logic to find all the DOM elements that need to be changed. There will also be one CSS file that holds all the filters being applied to the webpage.

### Group Members

Andrew Wong:
- Research color-blindness
- Determine what filters will be the most helpful
- Write the algorithm to find DOM elements
- Write Chrome Store page

Steve Olsen:
- Research Chrome extensions
- Use JQuery to get the elements and be able to insert
- Style the extension
- Write the README and Demo site

### Implementation Timeline

##### Phase 1
- More research into Chrome extensions from [here](https://developer.chrome.com/extensions/overview)
- End of day goal: Have a basic extension working

##### Phase 2
- Use jQuery to find the image tags
- Apply a filter to those tags

##### Phase 3
- jQuery to search for colored text, buttons, etc.
- Apply filters to whole pages as an option
- Allow toggling of: on, images only, text only, and off

##### Phase 4
- Test with people who are color-blind
- Make demo site

##### Phase 5
- Style
- Push to Chrome store

##### Bonus
- [ ] Port to other browsers (Firefox/Safari)
- [ ] Website black/white list options
