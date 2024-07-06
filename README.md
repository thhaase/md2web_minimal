# md2web Minimal Example

This is a minimal example of a better version of the [markdown2website](https://github.com/thhaase/markdown2website) tool I created a while ago. 

It uses the Fetch API, which is not supported by old browser versions.

### What's New?
- "Lighter"
- Easier to modify 
- Better/more intuitive markdown parser 

### Explanation

- `index.html` renders the whole website
- `files.json` contains the list of files that are displayed on the start page. Just add your file into the folder and add it to `files.json` to be displayed
- `src/_footer.html` is the footer of the webpage
- `src/_header.html` is the header of the webpage which contains the navigation bar
- `src/markdownparser.js` is the markdown parser I stole from Christopher Jeffrey (copyright information is in the first lines of the file)
- `src/icons` contains icons that are automatically displayed when a certain file type is recognized in a linked .md or .pdf file
