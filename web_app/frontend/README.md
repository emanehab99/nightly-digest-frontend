## The Nightly Digest Frontend Application

### Setup dev environment
This is the frontend app for The Nightly Digest. It is built with React, Shadcn component library and Tailwind CSS for styling.

Vite is used as a build tool. It provides a development server with fast-refresh enabled.
#### Prerequisites
- Install latest LTS node version >= v22 according to [instructions](https://nodejs.org/en/download)
- Verify node installation
```
    node -v
    npm -v
```
#### Getting started
- Clone the repo
```
    git clone https://github.com/emanehab99/nightly-digest-frontend
    cd nightly-digest/src/frontend
```

- Install dependencies
```
    npm install
```
- Start server
```
    npm run dev
```

### Shadcn
shadcn is already configured.
- configurations go in `src/components.json`
- Follow instructions in the [docs](https://ui.shadcn.com/docs) to install a component
- Installed components go in `src/components/ui/`

### Styling with Tailwind CSS
Tailwind is already configured. Global styles and configurations go in:

- `src/index.css` 
- `tailwind.config.js`

