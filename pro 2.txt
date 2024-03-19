class Animal {
    void makeSound() {
        System.out.println("Animals make  sound");
    }
}

class Dog extends Animal {
    void makeSound() {
        System.out.println("barks");
    }
}

class Cat extends Animal {
    void makeSound() {
        System.out.println("meows");
    }
}

public class TestPolymorphism {
    public static void main(String[] args) {
        Animal animal = new Animal();
        Animal dog = new Dog();
        Animal cat = new Cat();
        animal.makeSound();
        dog.makeSound();
        cat.makeSound();
    }
}