# Blazor-Template-Tailwindcss

This is template application for creating a Blazor Server App using Tailwind CSS and the Tailwind CLI. It is based on the default dotnet Blazor Server App project but cleaned for bootstrap and redesigned with Tailwind CSS components.

This is based on [Chris Sainty's](https://chrissainty.com/) great talk about building blazor applications with Tailwind CSS. Following his talk I have created the same application as he builds in the talk, but based it on the default dotnet project instead of a custom blazor project.

## Get started with this project

1. Clone this repository. 
2. node install tailwindcss
```terminal
npm install -D tailwindcss
```
3. Navigate to the root of the project and start the Tailwind CLI buildproces. This will watch the project files and update the app.css file while you work.
```
npx tailwindcss -i .\Styles\app.css -o .\wwwroot\css\app.css --watch
```



### Links:

* [Chris Sainty's blazor repo: talk-building-beautiful-blazor-apps-with-tailwind](https://github.com/chrissainty/talk-building-beautiful-blazor-apps-with-tailwind)
* [Building beautiful Blazor apps with Tailwind CSS - Chris Sainty - NDC Copenhagen 2022](https://www.youtube.com/watch?v=rlRNsCGQlOg)
* [Install Tailwind CSS](https://tailwindcss.com/docs/installation)