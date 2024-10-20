# AstroX10

![GitHub followers](https://img.shields.io/github/followers/AstroX10?style=social)
![Twitter Follow](https://img.shields.io/twitter/follow/AstroX10?style=social)

## About Me

Hello! I'm AstroX10, a passionate JavaScript expert specializing in reverse engineering, fixing, and maintaining complex JavaScript software. With years of experience under my belt, I'm dedicated to solving the most challenging problems in modern web development.

### What I Just Do

- **Reverse Engineering**: Unraveling complex codebases
- **Debugging**: Finding and fixing elusive bugs
- **Performance Optimization**: Making JavaScript run at light speed
- **Modern Frameworks**: Expert in React, Vue, Angular, and more
- **Full-Stack Development**: From frontend to backend, I've got you covered

## Technologies & Tools

<p align="left">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="typescript" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/>
  <img src="https://www.vectorlogo.zone/logos/kubernetes/kubernetes-icon.svg" alt="kubernetes" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/photoshop/photoshop-line.svg" alt="photoshop" width="40" height="40"/>
  <img src="https://www.vectorlogo.zone/logos/adobe_illustrator/adobe_illustrator-icon.svg" alt="illustrator" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/aftereffects/aftereffects-original.svg" alt="after effects" width="40" height="40"/>
</p>

## GitHub Stats

![AstroX10's GitHub stats](https://github-readme-stats.vercel.app/api?username=AstroX10&show_icons=true&theme=radical)

## Featured Project

Here's a sneak peek at one of my recent projects:

```typescript
import { Observable, of } from 'rxjs';
import { map, catchError } from 'rxjs/operators';

interface User {
   id: number;
   name: string;
}

function getUser(id: number): Observable<User> {
   return of({ id, name: 'AstroX10' }).pipe(
       map(user => ({
           ...user,
           name: user.name.toUpperCase()
       })),
       catchError(error => {
           console.error('Error fetching user:', error);
           return of({ id: -1, name: 'ERROR' });
       })
   );
}
```

This snippet showcases my expertise in RxJS and TypeScript, demonstrating error handling and data transformation in a reactive programming paradigm.

## Get in Touch

<p align="left">
  <a href="https://whatsapp.com/channel/0029VasMxnC7Noa3nZk9QA3G" target="_blank"><img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp"></a>
  <a href="https://t.me/@FXastro0010" target="_blank"><img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram"></a>
  <a href="https://discord.com/danielfx0010" target="_blank"><img src="https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white" alt="Discord"></a>
  <a href="https://github.com/AstroX10" target="_blank"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>
</p>
