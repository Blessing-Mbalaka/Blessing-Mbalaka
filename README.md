public class PublicProfile {

    public static void main(String[] args) {
        new Profile("Blessing").display();
    }
}

class Profile {

    private String name;

    public Profile(String name) {
        this.name = name;
    }

    public void display() {
        System.out.println("=== " + name.toUpperCase() + " ===");
        System.out.println("> Building the future with code");
        System.out.println("> Passionate about software & innovation");
        System.out.println("> Always learning, always shipping ");
    }
}
