## Hi, I'm Philip! 👋

```java
interface Programmer { void code(); }
interface Student { void student(); }
interface Musician { void play(); }
interface Teacher { void teach(); }
interface Learner { void learn(); }

public class Individual implements Programmer, Student, Musician, Teacher, Learner {

    @Override public void code() { programmer.code(); }
    @Override public void student() { student.student(); }
    @Override public void play() { musician.play(); }
    @Override public void teach() { teacher.teach(); }
    @Override public void learn() { learner.learn(); }

    private final Programmer programmer = () ->
        System.out.println("💻 writing clean, concurrent code in go, java, python3, typescript, and c++");

    private final Student student = () ->
        System.out.println("🎓 systems and architecture + info internetworks at Georgia Tech"); 

    private final Musician musician = () ->
        System.out.println("🎸 clarinetist, pianist");

    private final Teacher teacher = () ->
        System.out.println("📚 physics teacher, digital design TA");

    private final Learner learner = () ->
        System.out.println("""🧩 lifelong learner, currently interested in distributed systems, cloud-native backends,
                            multi-agent AI systems, and post-rock, post-punk. 

                           previously interested in pure mathematics, history, theoretical physics""");

    private void introduce() {
        System.out.println("Hey, thanks for stopping by! Feel free to contact at pwu320@gatech.edu"); 
    }

    public static void main(String[] args) {
        var me = new Individual();
        me.introduce(); 
        me.code();
        me.student(); 
        me.play();
        me.teach();
        me.learn();
    }
}
```
## 🧰 Technologies & Tools

### Developer Tools
![VS Code](https://img.shields.io/badge/VSCode-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![PyCharm](https://img.shields.io/badge/PyCharm-000000?style=for-the-badge&logo=pycharm&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab%20CI%2FCD-FCA121?style=for-the-badge&logo=gitlab&logoColor=white)

### Cloud Services and Databases 
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white&logoWidth=40)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white&logoWidth=40)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white&logoWidth=40)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white&logoWidth=40)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white&logoWidth=40)

### Languages 
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white&logoWidth=40)
![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white&logoWidth=40)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white&logoWidth=40)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white&logoWidth=40)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white&logoWidth=40)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black&logoWidth=40)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white&logoWidth=40)

### Frontend Frameworks and Libraries 
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black&logoWidth=40)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white&logoWidth=40)
![React Flow](https://img.shields.io/badge/React%20Flow-0099FF?style=for-the-badge&logo=react&logoColor=white&logoWidth=40)
![React Router](https://img.shields.io/badge/React%20Router-CA4245?style=for-the-badge&logo=reactrouter&logoColor=white&logoWidth=40)
![Mapbox](https://img.shields.io/badge/Mapbox-000000?style=for-the-badge&logo=mapbox&logoColor=white&logoWidth=40)

### Backend Frameworks and Libraries 
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white&logoWidth=40)
![Gin](https://img.shields.io/badge/Gin-00C1B4?style=for-the-badge&logo=go&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white&logoWidth=40)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white&logoWidth=40)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white&logoWidth=40)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white&logoWidth=40)
![gRPC](https://img.shields.io/badge/gRPC-00C7B7?style=for-the-badge&logo=grpc&logoColor=white&logoWidth=40)


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
