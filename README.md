## Hi there 👋

```nix
{ pkgs ? import <nixpkgs> {} }:
pkgs.mkGitHubPage {
  name = "👤 Stepan Zhukovsky";
  profile = "👥 MOIS3Y";
  age = "3️⃣ 4️⃣ fourth decade";
  languages = [
    "🇷🇺 ru" 
    "🇺🇸 us"
  ];
  goal: "🎯 Make the world a better place"
  whoami = ''
    💘 Information Technology is my passion.
    🐍 I write primarily in Python3.
    🆓 I'm getting carried away:
      🔘 GNU/Linux ricing,
      🔘 OpenSource development,
      🔘 Manufacturing of leather goods
      🔘 Playing the piano,
    👪 Married, raising a daughter
  '';
}
```
