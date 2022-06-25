<h1 align="center"> Ignite Lab - Event Platform </h1>

![home](https://drive.google.com/uc?export=view&id=1HR50w18Q8crVeUAohravxWQGQ5fXQyyM)
![event](https://drive.google.com/uc?export=view&id=13p3wymff2-ecKzy0f2xvPiKiuiaNqHVQ)


## 💻 Project
Video platform developed using React, Apollo and GraphCMS. For study purposes, learning how to integrate front-end with API graphQL using CodeGen.
This app was developed during the Rockeseat Ignite Lab, on June 2022.

<a href="https://ignite-lab-react-git-main-andreiafsouza.vercel.app/">Here you can access the app</a>

## ✨ Technologies

-   [ ] React 
-   [ ] TypeScript
-   [ ] Apollo
-   [ ] GraphCMS
-   [ ] Tailwind CSS
-   [ ] Phosphor Icons

## :hammer_and_wrench: Features 

-   [ ] Subscribe name and email to access content
-   [ ] Video platform where you can select a specific class displaying the video file alongside title, description and teacher responsable for the class.

## 💻 Layout

You can access the original layout [right here](https://www.figma.com/file/7PVeN1H1TlnGrkBgYI2YLU/Plataforma-de-evento---Ignite-Lab-(Community)). You need to have a [Figma](http://figma.com/) account to access and duplicate the layout.

## Running the Project

You need to clone [this project](https://app.graphcms.com/clone/d1864e9892d44564950fa4d4d8905e44?name=Ignite%20Lab%20-%20Andreia%20Souza) in order to get all data needed to run the app.
Once cloned, go to your project settings/api-access to get your content api url and create your own permanent auth token.

After that, you'll need to create a .env.local in your root folder with the following environment variables, using your content api url and auth token

 ```cl
VITE_API_URL =
VITE_API_ACCESS_TOKEN =
```
You can use **npm install** to install all dependencies.
After that, just initialize the project.

```cl
npm run dev
```
