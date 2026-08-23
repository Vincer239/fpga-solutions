# FPGA Solutions
The official website of FPGA Solutions. 
We build your embedded desires, FPGA based of course.

## Installation
You can clone the project directly from this repo to your local system.
Installation prerequisites: nodejs, npm (or yarn or pnpm). 

Development has been done with nodejs: 22.21.1 and npm: 10.9.4

Install it from the [nodejs website](https://nodejs.org/en/download)
```bash
# Download and install nvm:
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.3/install.sh | bash

# in lieu of restarting the shell
\. "$HOME/.nvm/nvm.sh"

# Download and install Node.js:
nvm install 22

# Verify the Node.js version:
node -v # Should print "v22.21.1".

# Verify npm version:
npm -v # Should print "10.9.4".
```

### 1. Clone the repo

```bash
git clone https://github.com/vincer239/fpga-solutions.git
```

### 2. Install Dependencies

```bash
# (used)
npm install
# or
yarn install
# or
pnpm install
```

### 3. Start development Server

```bash
# (used)
npm run dev
# or
yarn dev
# or
pnpm dev
```

### Preview & Build

```bash
# (used)
npm run preview
npm run build
# or
yarn preview
yarn build
# or
pnpm preview
pnpm build
```

## Project Structure

Inside your Astro project, you'll see the following folders and files:

```
/
├── public/
│   └── ...
├── src/
│   ├── components/
│   │   └── ...
│   ├── layouts/
│   │   └── ...
│   └── pages/
│       └── ...
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

Any static assets, like images, can be placed in the `public/` directory.

## TailwindCSS

TailwindCSS is already configured in this repo, so you can start using it without any installation.

## Credits
AstroShip by [Web3Templates](https://web3templates.com")

[Hero Illustration](https://www.figma.com/community/file/1108400791662599811) by [Streamline](https://www.streamlinehq.com/)

