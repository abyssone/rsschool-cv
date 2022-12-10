# Pivovarov Dmitry
---
## Contacts
* Russia, Penza
* Phone: +7 963 102 70 14
* Email: sprenex@gmail.com
* GitHub: [***github/abyssone***](https://github.com/abyssone)
---
## About me

I have a secondary technical education in the specialty "computer networks and complexes". Year of experience in commercial development of programs for microcontrollers stm32 in C++. I study front-end technologies in order to change my occupation and develop as a full-stack web developer.

---
## Skills

* HTML5/CSS3, Bootstrap
* JavaScript
* NodeJS
* Git

---
## Code example

```
import { fork } from 'child_process';
import * as url from 'url';

const __dirname = url.fileURLToPath(new URL('.', import.meta.url));

const scriptPath = `${__dirname}/files/script.js`;

const spawnChildProcess = async (args) => {
    fork(scriptPath, [...args.split(' ')])
        .on('exit', (code) => console.log(`Closed with code ${code}`));
};

spawnChildProcess('').then(() => {
    console.log('hello im main');
})
```
---
## Experience

### Education:
* Zarechensk Institute of Technology
* Penza State Technological Institute
* Courses:
  + RS School Frontent
  + RS School NodeJS

---
## English

Pre-intermediate


