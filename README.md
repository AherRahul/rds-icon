<p align="center">
 <a href="https://rahulaher.netlify.app">
  <img src="https://rahulaher.netlify.app/img/logo/glyph-black-colored.svg" alt="Rahul Aher" width="250" />
 </a>
</p>

<p align="center">
  <a href="https://github.com/aherrahul/rds-icon/blob/main/LICENSE"><img src="https://img.shields.io/github/license/aherrahul/rds-icon" alt="License"></a>
  <a href="https://github.com/aherrahul/rds-icon"><img src="https://img.shields.io/jsdelivr/npm/hy/@aherrahul/rds-icon" alt="Downloads"></a>
  <a href="https://bundlephobia.com/package/@aherrahul/rds-icon" target="_blank"><img src="https://img.shields.io/bundlephobia/minzip/@aherrahul/rds-icon" alt="minzipped size"></a>
  <a href="https://www.npmjs.com/package/@aherrahul/rds-icon"><img src="https://img.shields.io/npm/v/@aherrahul/rds-icon" alt="Version"></a>
  <a href="https://github.com/aherrahul/rds-icon/pulls"><img src="https://img.shields.io/github/issues-pr/aherrahul/rds-icon" alt="Pull Request"></a>
  <a href="https://github.com/aherrahul/rds-icon/issues"><img src="https://img.shields.io/github/issues/aherrahul/rds-icon" alt="Issues"></a>
</p>


<h1 align="center">
  RDS Icons
</h1>


RDS-icons is a powerful and flexible icons design system built with Vue.js, aimed at providing a consistent and efficient way to develop user interfaces. With a collection of reusable components and styles, RDS-icons helps streamline your development process, ensuring your applications have a cohesive look and feel.

RDS Icons are packaged up and published to npm. We only include the processed SVGs in this package—it's up to you and your team to implement. Read our docs for usage instructions.

The iconography we use in RDS simplifies user interaction with the system, as it allows elements to be more easily identified. Furthermore, it allows users to more easily understand the layout components, reducing the learning curve on the interface.


## Purpose of @aherrahul/rds-icons

The purpose of @aherrahul/rds-icons is to provide developers with a vast selection of customizable icons while minimizing vendor lock-in. This package allows you to:

1. **Choose from an extensive library** of icons across different styles.
2. **Integrate custom icons** with ease, ensuring your designs remain unique.
3. **Use open-source tools and icon data** that empower you to customize icons without being tied to a specific set or vendor.


## Prerequisites

Before you begin, make sure you have the following installed:

- Node.js (v12 or higher)
- npm (v6 or higher) or Yarn (v1.22 or higher)
- Vue.js (v2.x or v3.x)


## NPM Package

[@aherrahul/rds-icons](https://www.npmjs.com/package/@aherrahul/rds-icons)


### Step 1: Install RDS-Icon

To use RDS in your Vue.js project, you first need to install it via npm. Open your terminal and run the following command:

```bash
npm install @aherrahul/rds-icons
```

Alternatively, if you prefer using Yarn, you can run:

```bash
yarn add @aherrahul/rds-icons
```

### Step 2: Import RDS-Icon in Your Project

Once the installation is complete, you need to import RDS into your Vue.js project. This can be done in your main JavaScript file (usually main.js or main.ts).

```

import { completeIconSet } from '@aherrahul/rds-icons/dist';

```

### Step 3: Using RDS-Icons
RDS implements a component-shaped wrapper for RDSIcons icons . Any maintenance or improvements must be made to the respective project and design kit in Figma and, if necessary, updated here.

```vue

<rds-icon
	name="box-outline"
	height="40"
	width="40"
	color="#36424E"
></rds-icon> 

```

## The Future of @aherrahul/rds-icons
Moving forward, I plan to enhance the package with additional icon sets, improved framework support, and better customization tools. This growth will be driven by community feedback and support. Contributions from users are welcomed, as they play an essential role in refining and expanding the library.

## Support and Contact
If you're using @aherrahul/rds-icons, your feedback is always appreciated! Consider joining the community, offering suggestions, or contributing to the codebase. Every bit of support helps in expanding and enhancing the package, ultimately benefiting developers everywhere.


Thank you for choosing @aherrahul/rds-icons for your icon needs. I look forward to seeing how you use it in your projects!

Happy coding!