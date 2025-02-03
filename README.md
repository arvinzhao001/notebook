# Welcome to [Slidev](https://github.com/slidevjs/slidev)!

To start the slide show:

- `npm install`
- `npm run dev xxx.md`
- visit <http://localhost:3030>

Edit the [xxx.md](./slides.md) to see the changes.

Learn more about Slidev at the [documentation](https://sli.dev/).

# Hosting 
Using [Github Actions](https://sli.dev/guide/hosting#github-pages) to deploy your project, Check [Github Config Page](https://github.com/arvinzhao001/slidev/settings/pages)

## Host a different presentation
1. Configure [package.json](./package.json) build command, specify xx.md and output dir
2. Configure the output dir above to [deploy.yml](./.github/workflows/deploy.yml), yaml path: jobs#build#steps#with#path
3. Save configuration, then push to the git remote, will auto trigger build and deploy
4. Access your slides. Example: https://arvinzhao001.github.io/slidev/1 
