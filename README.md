# Ahlan wa Sahlan <picture><img src="https://media0.giphy.com/media/5HyXGsoFzXWPKFx07j/giphy.gif?ep=v1_stickers_search&rid=giphy.gif&ct=s" width="50"></picture>
### Peace be upon you <picture><img src="https://media0.giphy.com/media/AQyuyk6LiCtT6Fcuim/giphy.gif?ep=v1_stickers_search&rid=giphy.gif&ct=s" width="25"></picture>

### I am **Kebal**, a Software Developer based in Malaysia 🇲🇾.
I enjoy building things and have developed many web-based systems — ranging from passion projects to production environments.

## Get to Know Me

Run this in your terminal to connect with me:
```
npx kebal
```

```vue
<script setup>
import { reactive, computed, onMounted } from 'vue';

// 👨‍💻 About Me
const profile = reactive({
    name: 'Kebal',
    pronouns: 'he/him/his',
    position: 'Software Developer',
    location: 'Malaysia 🇲🇾',
    languages: ['Malay', 'English'],
    technologies: {
        backEnd: ['Laravel', 'PHP', 'Yii2', 'WordPress'],
        frontEnd: {
            js: ['Vue.js', 'Nuxt.js', 'Alpine.js'],
            css: ['TailwindCSS', 'Bootstrap 5', 'SCSS'],
        },
        mobile: ['SwiftUI'],
        database: ['MySQL', 'MongoDB', 'Redis'],
        devOps: ['Linux', 'GitHub Actions', 'EC2', 'Cloudflare'],
        tools: ['Git', 'Postman', 'Figma', 'Nginx'],
        architecture: ['SPA', 'MVC']
    },
    // ☕ Vital Systems
    canCodeWithoutCoffee: false, 
});

const summary = computed(() => `${profile.name} | ${profile.position}`);

onMounted(() => console.log(summary.value));
</script>
```

