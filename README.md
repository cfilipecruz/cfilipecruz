<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=150&section=header"/>

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=35&pause=1000&color=00f2ea&center=true&vCenter=true&width=1000&lines=Hey+there!+I'm+Filipe+Cruz;Welcome+to+my+coding+corner;Grab+a+coffee+and+explore+my+projects!)](https://git.io/typing-svg)

<div align="center">
  <canvas id="p5Canvas"></canvas>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/1.4.0/p5.js"></script>
  <script>
    function setup() {
      let canvas = createCanvas(windowWidth, 300);
      canvas.parent('p5Canvas');
      frameRate(30);
    }

    function draw() {
      background(13, 17, 23);
      let time = millis() / 1000;
      let numCubes = 20;
      let size = 20;
      for (let i = 0; i < numCubes; i++) {
        let x = map(i, 0, numCubes, 0, width);
        let y = height / 2 + sin(time + i * 0.5) * 50;
        let alpha = map(i, 0, numCubes, 50, 255);
        fill(2, 169, 247, alpha);
        noStroke();
        rect(x, y, size, size);
        stroke(255);
        line(x, y + size / 2, width / 2, height / 2);
      }
    }
  </script>
</div>

## 🚀 About Me

Hey, I'm Filipe Cruz from Portugal! 🌍 A passionate developer with a degree in Computer Graphics and Multimedia Engineering. I thrive on solving problems creatively and continuously seek opportunities for growth. Fun fact: I built an intelligent greenhouse for my final project in my Electronics and Computer Systems course! 🏡

- 🌐 **Website:** [myskillhub.pt](https://myskillhub.pt)
- 💼 **LinkedIn:** [linkedin.com/in/cfilipecruz](https://www.linkedin.com/in/cfilipecruz)

## 💻 Technologies & Tools

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![Angular](https://img.shields.io/badge/angular-%23DD0031.svg?style=for-the-badge&logo=angular&logoColor=white)
![Ionic](https://img.shields.io/badge/ionic-%233878FF.svg?style=for-the-badge&logo=ionic&logoColor=white)
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=java&logoColor=white)
![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
![Node.js](https://img.shields.io/badge/node.js-43853D.svg?style=for-the-badge&logo=node-dot-js&logoColor=white)

## 🎮 Hobbies & Interests

- 🧪 Science & Technology
- 🚀 Entrepreneurship
- 📈 Investment
- 💪 Gym
- 🎮 Video Games & Sound
- 🤝 Volunteer Work
- 💻 Programming in various languages (JSON, p5.js, Ionic, Java, Linux, Kotlin, UML, Node.js, Python)
- 🎨 3D Animation & Modeling

## 🤝 Soft Skills

- Adaptability
- Conflict Resolution
- Creativity
- Critical Thinking
- Curiosity
- Empathy
- Initiative
- Integrity
- Open-mindedness
- Positivity
- Problem-solving
- Project Management
- Resilience
- Teamwork
- Transparency
- Honesty

## 🛠 Tools

- GitHub / Bitbucket
- Adobe Tools
- Xampp
- Maya 3D / Blender
- Trello
- Raspberry Pi
- Arduino
- Visual Studio Code
- Microsoft Tools
- Android Studio
- Unreal Engine / Unity
- PostMan
- PHP Storm
- NetBeans
- Report Designer
- Confluence / Jira

<div align="center">
  <br>
  <p align="center">
    <b>Visitors Count</b>
  </p>
  <p align="center">
    <img align="center" src="https://profile-counter.glitch.me/{cfilipecruz}/count.svg" />
  </p>
  <br>
</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=150&section=footer"/>
