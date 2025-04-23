```java
public class DeveloperProfile {

    public static void main(String[] args) {
        Introduction.print();
        TechStack.print();
        ComingSoon.print();
    }
}

// 🧑‍💻 Introduction Section
class Introduction {
    public static void print() {
        System.out.println("👋 Hi there!");
        System.out.println("I'm a curious and driven software developer who lives between backend logic and frontend magic.");
        System.out.println("I create applications that solve real problems — with clean architecture, maintainable code, and a constant hunger to improve.\n");
    }
}

// 🛠 Tech Stack Section
class TechStack {

    public static void print() {
        System.out.println("🔧 Tech Stack Overview\n");

        printCategory("Backend", "Java", "Spring Boot", "Hibernate", "Node.js", "Express.js");
        printCategory("Frontend", "React.js", "Vue.js", "AngularJS", "React Native", "Expo", "Android Studio");
        printCategory("Databases", "MongoDB", "MySQL", "PostgreSQL", "Elasticsearch", "Supabase");
        printCategory("Libraries & Frameworks", "Spring Boot", "Hibernate", "Redux", "Axios", "Bootstrap", "Material-UI", "Tailwind CSS");
        printCategory("Tools", "Postman", "GitKraken", "Docker", "Power BI");
        printCategory("Version Control & CI/CD", "Git", "GitHub", "GitLab");
    }

    private static void printCategory(String category, String... technologies) {
        System.out.println("📁 " + category + ":");
        for (String tech : technologies) {
            System.out.println("  - " + tech);
        }
        System.out.println();
    }
}

// 🚧 Projects Coming Soon
class ComingSoon {
    public static void print() {
        System.out.println("🚧 Personal projects in progress. Coming soon!");
    }
}

