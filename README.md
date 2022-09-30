# Introduction to doc-site

We at FifthTry designed and developed `FTD` langauge for you. Using our own `FTD`
language `doc-site` is designed for you to create your documentation sites. 

Check out our simple and easy [documentation](https://fifthtry.github.io/doc-site/documentation/docs/) to learn more about 
`doc-site`.

## 🚀 Project Structure:

Inside of your `doc-site` project, you'll see the following folders and files:
```
.
├── .build/
│   └── index.html
│
├── .packages/
│   └── fifthtry.github.io/
│   	└── All downloaded dependencies
│
├── blog-articles/
│	├── category-1/
│   │	├── index.ftd
│   │   ├── sample-post-1.ftd
│   │   └── sample-post-2.ftd
│   │
│   └── category-2/
│   	├── index.ftd
│       ├── sample-post-3.ftd
│       └── sample-post-4.ftd
│
├── blog-authors/
│   ├── abrar.ftd
│   ├── amitu.ftd
│   ├── arpita.ftd
│   └── ganesh.ftd
│
├── documentation/
│   ├── blog-docs.ftd
│   └── docs.ftd
│
├── static/
│   └── All images and static assets included in doc-site
│
├── FPM.ftd
├── index.ftd
├── featured-posts.ftd
├── floater.ftd
├── image.ftd
├── LICENSE
└── README.md
```

## Commands

All commands are run from the root of the project, from a terminal:

```
=======================================================================
| Command                | Action                                     |
| :--------------------- | :----------------------------------------- |
| fpm build              | FPM builder installs all `FPM` dependencies|
| fpm serve              | Starts local dev server at available port  |
|                        | `localhost:8000`                           |
=======================================================================
```

## 👀 Want to learn more?

Feel free to check [our documentation](https://fpm.dev/) or jump into our [FifthTry Discord server](https://discord.gg/bucrdvptYd).
