### I am [Daniel](https://github.com/FXastro)

```javascipt
class Person {
  #age;
  constructor(name, age) {
    this.name = name;
    this.#age = age;
  }

  get age() {
    return this.#age;
  }

  set age(newAge) {
    if (newAge > 0) this.#age = newAge;
  }

  introduce() {
    return `My name is ${this.name}`;
  }
}

class Teenager extends Person {
  constructor(name, age, hobby) {
    super(name, age);
    this.hobby = hobby;
  }

  introduce() {
    return `${super.introduce()} and I'm ${this.age}. I like ${this.hobby}.`;
  }
}

class Utility {
  static prefix = "Output:";

  static print(message) {
    console.log(`${this.prefix} ${message}`);
  }
}

const daniel = new Teenager("Daniel", 16, "coding");
Utility.print(daniel.introduce());
```

- 🔭 I’m currently working on **Check My Repos**
- 🌱 Learning everything about **Scalable Application Development**
- 💪🏼 Future Goals: Explore more cloud technologies and never stop creating new ideas and be rich.


##### Computer Communications I Intract with

![JavaScript](https://img.shields.io/badge/-JavaScript-000000?style=flat&logo=javascript)
![Python](https://img.shields.io/badge/-Python-000000?style=flat&logo=python)
![HTML5](https://img.shields.io/badge/-HTML5-000000?style=flat&logo=html5)
![CSS3](https://img.shields.io/badge/-CSS3-000000?style=flat&logo=css3)
![Tailwind CSS](https://img.shields.io/badge/-Tailwind%20CSS-000000?style=flat&logo=tailwind-css)
![Bootstrap](https://img.shields.io/badge/-Bootstrap-000000?style=flat&logo=bootstrap)

##### Some of the technologies I have worked with

![Node.js](https://img.shields.io/badge/-Node.js-222222?style=flat&logo=node.js&logoColor=339933)
![Express.js](https://img.shields.io/badge/-Express.js-222222?style=flat&logo=express)
![MongoDB](https://img.shields.io/badge/-MongoDB-222222?style=flat&logo=mongodb)
![Sequelize](https://img.shields.io/badge/-Sequelize-222222?style=flat&logo=sequelize)
![Git](https://img.shields.io/badge/-Git-222222?style=flat&logo=git&logoColor=F05032)
![GitHub](https://img.shields.io/badge/-GitHub-222222?style=flat&logo=github&logoColor=181717)
![Heroku](https://img.shields.io/badge/-Heroku-222222?style=flat&logo=heroku)
![Render](https://img.shields.io/badge/-Render-222222?style=flat&logo=render)
![Koyeb](https://img.shields.io/badge/-Koyeb-222222?style=flat&logo=koyeb)
![Amazon Web Services](https://img.shields.io/badge/-Amazon%20Web%20Services-222222?style=flat-square&logo=Amazon-Web-Service)
![Google Cloud](https://img.shields.io/badge/Google%20Cloud-black?style=flat-square&logo=google-cloud)
![Tailwind CSS](https://img.shields.io/badge/-Tailwind%20CSS-000000?style=flat&logo=tailwind-css)

---
