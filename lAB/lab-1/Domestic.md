```java
class Animal{
    String name;
    String food;
    Animal(){ //Default Constructor
    name = "Dog"; 
}
    Animal(String food){//parameterized constroctor
        this.food = food;
    }
    
}
class Domestic{
    public static void main(String[] args){
        Animal Dog = new Animal("meat");
        System.out.println("Domestic animal we are talking about is" + Dog.name);
        System.out.println("Dog eats " + Dog.food );
    }
}
```