[Github](https://batoolalali.github.io/401-Reading-notes/class27)


## React Testing
- Snapshots: Make assertions on the exact rendered markup.
- Render Testing: allows for jQuery-like inspection of the virtual DOM tree.
- Shallow Testing: Executes and renders the called/container component, but does not compose children.
- Mounting: Executes the full component and children. Allows for inspection of rendered Virtual DOM as well as the current state


## Deployment 
The node server is only there to aid in your development.
`$ npm run build`

### Github pages deploy
1. Create an empty repository on GitHub. 
2. Create a new React app on your computer. 
3. Install the gh-pages package as a "dev-dependency" of the app.
4. Create a git repository in the app's folder. 
5. Optionally, commit your source code to the "master" branch and push your commit to GitHub. 
