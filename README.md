public class MyProfile {

  public record Developer (
    String name,
    String role,
    String country,
    String currentJob,
    List<String> hobbies,
    String goal
  ) {}

  public static void main(String[] args) {
    final var srini = new Developer(
      "Srinivas",
      "Backend Architect",
      "India",
      "Architect",
      List.of("Car detailing", "Chess Player"),
      "Tech Architect"
    );

    while(true) {
      code(srini);
    }
  }

  public static void code(Developer dev) {
    System.out.printf("%s is coding..", dev.name());
  }
}
✨ I'm Srinivas ! ✨
💼 Working as Software Architect, specializing in Back-end Development at Inter&Co.
🚀 My stack is Java, Mulesoft, Spring Boot, PostgreSQL, AWS, Kafka, and Kubernetes.
