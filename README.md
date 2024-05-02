public class Car {
    // Fields (attributes)
    private String color;
    private String model;

    // Constructor
    public Car(String color, String model) {
        this.color = color;
        this.model = model;
    }

    public void displayInfo() {
        System.out.println("Car model: " + model + ", Color: " + color);
    }

    public static void main(String[] args) {
        Car myCar = new Car("Red", "Toyota Corolla");
        myCar.displayInfo();
    }
}
