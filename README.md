# Email for Teoriappar
This is an email built with Foundation for Emails. We use the Inky templating to make it easier too grasp the code.
It's important that you run the build process before uploading these templates to mailchimp.

All final and generated files will end up in the `dist` folder.
Your work files will be inside the `src` folder.

## Install Project
This will install all neede dependencies to run the project.

```bash
npm install
```

## Start project (for development)
This will start a dev enviroment.

```bash
npm start
```

## Build project.
This will build the project, compress images, inline all the CSS.

```bash
npm run build
```

## Upload to Mailchimp
Copy the follow files:
- index.html
- css folder
- assets folder

from your `dist` folder (after running `npm run build`).
Zip these files, and upload them to mailchimp.

## Mailchimp
I've added all mailchimp tags that are needed for unsubscribe links etc.
Ther are also template tags for hiding blocks. This means you can use and edit this template in Mailchimp once it's uploaded.