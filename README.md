import com.hy2n.Profile;

public class Main {
    public static void main(String[] args) {
        Person me = new Person();
        me.printFullName();
        me.printContacts();
    }
}

class Person implements Profile {
    public void printFullName() {
        System.out.println("donghyun Lee");
    }
    public void printContacts() {
        System.out.println("me@donghyun.cc");
    }
}
