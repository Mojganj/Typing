# Read Me

### Project Name :

- Speed Typing

---

### Project Link :

- Speed Typing - [click here]()

---

### Table of Contents

- [Description](#description)
- [How To Use](#how-to-use)
- [References](#references)
- [License](#license)
- [Author Info](#author-info)

---

## Description

Most jobs do not explicitly require certain typing speeds, but that's because basic typing skills are taken as a given. Thus, you should aim for a typing speed of at least 40 WPM to keep up a standard level of efficiency at work..However this project aim to help you to improve your typing speed by tracking your progress in each round and give you a score based on your typing speed and accuracy through a table of statistics.

The project might seems at the beginning easy to build but believe me, there are a ton of logics under the hook, at some point before starting building the project, i thought it may took maximum 1 week, at the end it turns out more than 20 days to build it with a clean code, note that first commits implementation of the project were locally meaning outside of Github.

---

## 📌Contribution :

Contribution to this repos are always welcome. You can alwas upgrade the UI, or fix any bug predefined in the issue section.

For new contibution or feature :

1. Open a new issue describing the feature.
2. Add feature tag to this issue.
3. Get acceptance from the code maintainers
4. Enjoy adding the feature

---

## Technologies & libraries

- Next.js
- TypeScript
- Tailwind CSS
- framer-motion

---

## Functionalities

- Stop Timer when the user stopped focus on typing
- Restart Typing by a keyboard Shortcut (Mac : Cmd + / OR Windows : Ctrl + /)
- Tracking each round statistics through a table
- Mobile Friendly

---

## How To Use

#### Installation & Set Up

##### Step 1 : cloning the repo to your local machine

```sh
    git clone https://github.com/Mojganj/Typing
```

##### Step 2 : Dependencies installation

in the root of the project "Typing", execute in your terminal the command "**_yarn_**"

###### **_Note: make sure you installed node & yarn package manager_**

##### Step 3 : Start the development server

```sh
    yarn dev
```

#### 🚀 Building and Running for Production

1. Generate a full static production build

   ```sh
   yarn build
   ```

---

## API Description :

##### Endpoint 1 :

the following endpoint will return a json object contains "quote" and "author", for current project i displayed only the quote, **minLength** is the minimum of characters.

```api
    /api/typing/[minLength]
```

##### notes :

- **_minLength_** should be between 10 - 300.
- the returned quote is a chain of
- i costumized the original Endpoint using The API Route of Nextjs, here is the Original Endpoint.

##### Original Endpiont :

###### URL :

```api
    https://api.quotable.io/random?minLength=[minLength]
```

example :

```api
    /api/userInfoByIP/150
```

###### **_Get Request to above endpoint will return the following json data :_**

```JavaScript
    {"quote":"Technology… is a queer thing. It brings you great gifts with one hand, and it stabs you in the back with the other.","author":"carrie-snow"}
```

---

### 🎨 Color Reference

- ![#64FFDA](https://via.placeholder.com/15/64FFDA/64FFDA.png)`#64FFDA`
- ![#0A192F](https://via.placeholder.com/15/0A192F/0A192F.png) `#0A192F`
- ![#D1D5DB](https://via.placeholder.com/15/D1D5DB/D1D5DB.png) `#D1D5DB`

---

## License

MIT License

Copyright (c) [2024] [Mojgan Jafari]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

---

[Back To The Top](#description) :
