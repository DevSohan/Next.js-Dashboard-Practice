# Next.js-Dashboard-Practice

A Guided Project by Next.js 

[Live Demo](https://next-js-dashboard-ten-amber.vercel.app/)

[Reference](https://nextjs.org/learn/dashboard-app/getting-started)


For test login, you can use the followings:
```bash
Email: user@nextmail.com
Password: 123456
```

  * [Project Overview](#Project-Overview)
  * [Technologies used](#technologies-used)
  * [Getting Started](#getting-started)
      - [Prerequisites](#prerequisites)
      - [Usage Instructions](#usage-instructions)
  * [Accessibility Testing](#accessibility-testing)
  * [License](#license)

## Project Overview

This is a fun project to learn about the NextJS along with the followings:

| CSS Styling                       | Static and Dynamic Rendering & Streaming  |
| Image and Link Components         |    Search and Pagination                  |
| Layouting                         | Errors Handling                           |
| Navigation                        | Accessibility                             |
| Database Connection               | Authentication                            |
| Skeleton                          | SEO                                       |

## Technologies used

This project was created using the following technologies.

- NextJS
- React
- TypeScript
- TailwindCSS
- CLSX
- Next-Auth
- PostgreSQL
- ZOD

## Getting Started

### Prerequisites

Before you begin, ensure you have the following software and tools installed on your machine:
   - **Node.js**: Version 14.x or higher. [Download Node.js](https://nodejs.org/en/download/package-manager)
   - **pnpm, npm or yarn**: Node.js package managers. npm comes bundled with Node.js.

**Note**: *pnpm* is a new package manager, NextJS suggested to use *pnpm* for this tutorial.

### Usage Instructions

In order to run this project locally, simply fork and clone the repository or download as zip and unzip on your machine. 

**1. Clone the Repository**

Start by cloning the repository to your local machine using git:

```
$ git clone https://github.com/DevSohan/next.js-dashboard
$ cd next.js-dashboard
```

**2. Set up Environment Variables**

In this application, you will only need to set up environment variables for PostgreSQL connection and Authentication Secret. You can use vercel account to create free database under a project and get the variable related to PostgreSQL. The following variables are required:

```bash
POSTGRES_URL=""
POSTGRES_PRISMA_URL=""
POSTGRES_URL_NO_SSL=""
POSTGRES_URL_NON_POOLING=""
POSTGRES_USER=""
POSTGRES_HOST=""
POSTGRES_PASSWORD=""
POSTGRES_DATABASE=""
AUTH_SECRET=""
```

**Note**: For creating *AUTH_SECRET*, run the following command and copy the generated key.

```bash
openssl rand -base64 32
```

**3. Install Dependencies**

Navigate to the next.js-dashboard directory and install the necessary dependencies:

```bash
cd ../next.js-dashboard
pnpm i
# or if using npm
npm install
# or if using yarn
yarn install
```

**4. Start the Application**

To start the application, run the following command:

```bash
cd ../next.js-dashboard
pnpm dev
# or
npm run dev
# or
yarn dev
```

The application should start on http://localhost:3000.

## Accessibility Testing

Coming Soon...


## License
The software in this project is licensed under the Apache License 2.0, a permissive open-source license. By using this software, you agree to the following terms:

**Summary of the Apache License 2.0**

1. **Freedom to Use**: You can use the software for any purpose, including commercial use, without paying royalties.
2. **Modification and Distribution**: You can modify the software and distribute it in either its original or modified form, as long as you include the original license and clearly mark any changes you made.
3. **Patent Rights**: The license grants you rights to any patents held by the contributors related to the software, but if you sue anyone over patent issues involving the software, your license and patent rights terminate.
4. **No Trademark Rights**: The license doesn’t grant permission to use the names, trademarks, or logos of the contributors.
5. **No Warranty**: The software is provided "as is," without any warranties, meaning the contributors aren't responsible for any issues or damages that arise from using it.
6. **Optional Support**: If you offer warranties, support, or assume additional liability when redistributing the software, you're responsible for those obligations, not the original contributors.

**Copyright Notice**

    Copyright 2024 Mohammad Sohanur Rahman

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
