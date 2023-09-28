<p align="center">
  <img src="https://github.com/marcelosantanamartins/marcelosantanamartins/blob/main/header-image.jpg" />
</p>

```js
import SoftwareDeveloper from 'marcelosantanamartins';

class Bio extends SoftwareDeveloper {
  name     = 'Marcelo Santana Martins';
  title    = 'Software Engineer';
  company  = 'QuintoAndar';
  location = 'São Paulo, Brazil';
}

class Skills extends SoftwareDeveloper {
  languages  = ['C#', 'JavaScript', 'PHP'];
  databases  = ['MySQL', 'SQL Server', 'PostgreSQL'];
  frameworks = ['Vue.js', '.NET'];  
  learning   = ['React', 'Java', 'Python'];
  
  // Other skills
  wordpress = true;
  sass      = true;
  jquery    = true;
  
  generateSkillsSection() {
    return `
## Skills

Here are some of my skills and knowledge:

- **Programming Languages:** ${this.languages.join(', ')}
- **Databases:** ${this.databases.join(', ')}
- **Frameworks:** ${this.frameworks.join(', ')}
- **Currently Learning:** ${this.learning.join(', ')}
- **WordPress:** ${this.wordpress ? 'Yes' : 'No'}
- **Sass:** ${this.sass ? 'Yes' : 'No'}
- **jQuery:** ${this.jquery ? 'Yes' : 'No'}
    `;
  }
}
```
<img alt="Marcelo's Top Languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=marcelosantanamartins&langs_count=8&layout=compact&theme=react&hide_border=true&bg_color=1F222E&title_color=F85D7F&icon_color=F8D866" height="128px"/>
