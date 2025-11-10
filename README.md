## Hi there 👋

```
interface Programmer { void code(); }
interface Musician { void play(); }
interface Teacher { void teach(); }
interface Learner { void learn(); }

public class Individual implements Programmer, Musician, Teacher, Learner {

    private final Programmer programmer = () ->
        System.out.println("💻 writing clean, modular code in go, java, python, typescript, and c++");

    private final Musician musician = () ->
        System.out.println("🎸 clarinetist, pianist, lover of rock and jazz");

    private final Teacher teacher = () ->
        System.out.println("📚 sharing knowledge, TAing for ECE 2031");

    private final Learner learner = () ->
        System.out.println("🧩 lifelong learner, currently interested in distributed systems, systems programming, cloud-native backends, and multi-agent systems");

    @Override public void code() { programmer.code(); }
    @Override public void play() { musician.play(); }
    @Override public void teach() { teacher.teach(); }
    @Override public void learn() { learner.learn(); }

    public static void main(String[] args) {
        var me = new Individual();
        System.out.println("✨ Hey! I'm Philip. Thanks for stopping by!");
        me.code();
        me.play();
        me.teach();
        me.learn();
    }
}
```
## 🧰 Technologies & Tools

## Cloud Services and Databases 
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=google-cloud&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

## Languages 
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)

## Frontend Frameworks and Libraries 
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React Flow](https://img.shields.io/badge/React%20Flow-0099FF?style=flat-square&logo=react&logoColor=white)
![React Router](https://img.shields.io/badge/React%20Router-CA4245?style=flat-square&logo=reactrouter&logoColor=white)

## Backend Framework and Libraries 
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-00C7B7?style=flat-square&logo=grpc&logoColor=white)




<!--
**philipxunwu/philipxunwu** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
