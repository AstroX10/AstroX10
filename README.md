### About Me

I'm a 16-year-old coding enthusiast with a passion for learning, creating, and solving complex problems through software development. Currently, I’m focused on building **scalable applications** and exploring **cloud technologies**. Check out my [repositories](https://github.com/FXastro) to see my latest projects!

### Learning

```typescript
class Person {
  #age: number;
  constructor(public name: string, age: number) {
    this.#age = age;
  }

  get age() {
    return this.#age;
  }

  set age(newAge: number) {
    if (newAge > 0) this.#age = newAge;
  }

  introduce() {
    return `My name is ${this.name}`;
  }
}

class Teenager extends Person {
  constructor(name: string, age: number, public hobby: string) {
    super(name, age);
  }

  introduce() {
    return `${super.introduce()} and I'm ${this.age}. I enjoy ${this.hobby}.`;
  }
}

const daniel = new Teenager("Daniel", 16, "coding");
console.log(daniel.introduce());
```

## Skills and Technologies

### Languages

![JavaScript](https://img.shields.io/badge/-JavaScript-000?style=flat&logo=javascript) ![TypeScript](https://img.shields.io/badge/-TypeScript-000?style=flat&logo=typescript) ![Python](https://img.shields.io/badge/-Python-000?style=flat&logo=python) ![HTML5](https://img.shields.io/badge/-HTML5-000?style=flat&logo=html5) ![CSS3](https://img.shields.io/badge/-CSS3-000?style=flat&logo=css3)

### Frameworks & Libraries

![Node.js](https://img.shields.io/badge/-Node.js-000?style=flat&logo=node.js&logoColor=339933) ![Express.js](https://img.shields.io/badge/-Express.js-000?style=flat&logo=express) ![Tailwind CSS](https://img.shields.io/badge/-Tailwind%20CSS-000?style=flat&logo=tailwind-css) ![Bootstrap](https://img.shields.io/badge/-Bootstrap-000?style=flat&logo=bootstrap)

### Databases & ORMs

![MongoDB](https://img.shields.io/badge/-MongoDB-000?style=flat&logo=mongodb) ![Sequelize](https://img.shields.io/badge/-Sequelize-000?style=flat&logo=sequelize) ![SQLite](https://img.shields.io/badge/-SQLite-000?style=flat&logo=sqlite)

### DevOps & Cloud

![Git](https://img.shields.io/badge/-Git-000?style=flat&logo=git) ![GitHub](https://img.shields.io/badge/-GitHub-000?style=flat&logo=github) ![Heroku](https://img.shields.io/badge/-Heroku-000?style=flat&logo=heroku) ![AWS](https://img.shields.io/badge/-AWS-000?style=flat&logo=amazon-web-services) ![Google Cloud](https://img.shields.io/badge/-Google%20Cloud-000?style=flat&logo=google-cloud) ![Render](https://img.shields.io/badge/-Render-000?style=flat&logo=render) ![Koyeb](https://img.shields.io/badge/-Koyeb-000?style=flat&logo=koyeb)
