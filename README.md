**Hi, I'm an Alias 👋**

```Typescript
export const aboutMe = (alias = 'Fluctlight Kayaba'): Me => ({
  name: alias,
  describe: "hype-driven sapien",
  code: ["Typescript/Node.js", "Rust", "Zig", "Nim", "Elixir"],
  interested: "writing: write software, write game, write novel, write song (intention, would be never happen)",
  hobbies: ["code", "game", "novel", "music", "talk".repeat(Number.MAX_SAFE_INTEGER)],
});

export interface Me {
  name: string;
  describe: string;
  code: string[];
  intestested: string;
  hobbies: string[];
}
```

<!--
- 🌱 Actually this is an alias account, the idea of being able to hide away and do really interesting things with an alias is just too cool, in my opinion.
- 📫 How to reach real me: lehaoson@gmail.com
- ⚡ Fun fact: there is no fun fact, it is not that fun.
