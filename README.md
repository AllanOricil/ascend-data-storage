# custom-node-red-node-es-template

![custom-nodes](./images/custom-nodes.png)

## 📁 Directory Structure

This project is built using the `nrg` cli.

```bash
node-red-node-es-template/
└── src/
    └── nodes/
        ├── node-1/
        │   ├── client/
        │   │   ├── i18n/
        │   │   │   ├── dictionaries/
        │   │   │   │   ├── de.json
        │   │   │   │   └── en-US.json
        │   │   │   └── docs/
        │   │   │       ├── de.html
        │   │   │       └── en-US.html
        │   │   ├── icons/
        │   │   │   └── icon-1.png
        │   │   ├── index.html
        │   │   └── index.js
        │   └── server/
        │       └── index.js
        └── node-2/
            ├── client/
            │   ├── i18n/
            │   │   ├── dictionaries/
            │   │   │   ├── de.json
            │   │   │   └── en-US.json
            │   │   └── docs/
            │   │       ├── de.html
            │   │       └── en-US.html
            │   ├── icons/
            │   │   └── icon-2.png
            │   ├── index.html
            │   └── index.js
            └── server/
                └── index.js
```

### dist

```bash
node-red-node-es-template/
└── dist/
    ├── icons/
    │   ├── icon-1.png
    │   └── icon-2.png
    ├── locales/
    │   ├── de/
    │   │   ├── index.html
    │   │   └── index.json
    │   └── en-US/
    │       ├── index.html
    │       └── index.json
    ├── index.html
    ├── index.js.map
    └── index.js
```

## 💻 Dev Environment Requirements

| Tool | Version |
| ---- | ------- |
| node | >= 18   |
| npm  | >= 10   |

## 📖 How to test your node

1. open a terminal in the root of this project
2. run `npm install`
3. run `npm run start` and wait for your browser to open
4. verify that 4 nodes are available in the pallete, in the "custom nodes" group.
