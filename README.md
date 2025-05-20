# Ahlan wa Sahlan <picture><img src="https://media0.giphy.com/media/5HyXGsoFzXWPKFx07j/giphy.gif?ep=v1_stickers_search&rid=giphy.gif&ct=s" width="50"></picture>
### Peace be upon you <picture><img src="https://media0.giphy.com/media/AQyuyk6LiCtT6Fcuim/giphy.gif?ep=v1_stickers_search&rid=giphy.gif&ct=s" width="25"></picture>

#### I am **Kebal**, a Software Developer based in Malaysia 🇲🇾.
I enjoy building things and thus far had built many web-based systems — both for fun and in production.

## Get to Know About Me

Hit in your console or terminal to connect with me.
```
npx kebal
```

```vue
<script setup>
import { reactive, computed, onMounted } from 'vue';

const profile = reactive({
    pronouns: 'he/him/his',
    position: 'Software Developer',
    languages: ['Malay', 'English', 'Indonesian'],
    technologies: {
        backEnd: ['Laravel', 'Native PHP', 'Yii2', 'WordPress'],
        frontEnd: {
            js: ['Vue.js', 'Nuxt.js', 'Alpine.js'],
            css: ['TailwindCSS', 'Bootstrap 5', 'SCSS', 'SASS', 'CSS'],
        },
        mobile: {
            frontEnd: ['SwiftUI'],
        },
        database: ['MySQL', 'SQLite', 'MongoDB', 'Redis', 'MariaDB'],
        devOps: ['Linux', 'Jenkins', 'GitHub Actions', 'EC2', 'S3', 'Cloudflare'],
        tools: ['Git', 'GitHub', 'Insomnia', 'Postman', 'Canva', 'Figma', 'Nginx', 'Monday.com'],
        misc: ['REST API', 'Chrome Extensions', 'WordPress Extensions'],
        os: ['Mac', 'Windows 11', 'Ubuntu'],
        architecture: ['SPA', 'MVC']
    },
    canCodeWithoutCoffee: 'no',
});

const summary = computed(() => `${profile.name} | ${profile.position}`);

onMounted(() => console.log(summary.value));
</script>
```

