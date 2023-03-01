# Code-for-Class-file-Cat.java-

public class Cat extends Animal implements IPettable {

    public Cat(String picture, String name, int age) {
        super(picture, name, age);
    }

    @Override
    public void madeSound() {
        System.out.println(this.name + " meowed!");
    }

    @Override
    public void pet() {
        System.out.println(this.name + " is such a happy pet");
    }
}
