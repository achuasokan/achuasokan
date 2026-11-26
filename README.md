<h1 align="center">Achu Asokan</h1>

<p align="center">
  Software Engineer &nbsp;|&nbsp; Full Stack Developer<br/>
  Web and Mobile Applications
</p>

<p align="center"><code>about.ts</code> &nbsp;·&nbsp; <code>stack.ts</code> &nbsp;·&nbsp; <code>interests.ts</code> &nbsp;·&nbsp; <code>terminal</code></p>

---

### about.ts

```ts
const developer = {
  name: "Achu Asokan",
  role: "Software Engineer",
  focus: "Full Stack Developer",
  builds: ["Web Applications", "Mobile Applications"],
  tagline: "From concept to creation.",
};

export default developer;
```

### stack.ts

```ts
export const stack = {
  frontend: ["React", "Next.js", "Vue.js", "TypeScript", "TanStack Query"],
  mobile:   ["React Native", "Expo"],
  backend:  ["Node.js", "Express", "NestJS"],
  database: ["PostgreSQL", "MongoDB"],
  systems:  ["Docker", "Socket.io"],
} as const;
```

### interests.ts

```ts
export const interests = [
  "Full Stack Web Development",
  "Mobile Application Development",
  "UI/UX Design",
  "Real-time Applications",
  "Building useful digital products",
];
```

### terminal

```bash
$ whoami
achuasokan

$ npm run build --product=useful
> compiling ideas...
> shipping...
> done. From concept to creation.
```
