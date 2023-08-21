class Animal {
  public void animalSound() {
    System.out.println("The animal makes a sound");
  }
}
    }
    Public class Landanimals
    public void landanimals() {
        String[] LandAnimalsTypes = {"snake", "cat", "dog"};
        System.out.println("Land Animals Types: " + Arrays.toString(LandAnimalsTypes));
    }
    Public class SeaAnimals
    public void Seaanimals() {
        String[] SeaAnimalsTypes = {"Shark", "Megalodon", "Prism+"};
        System.out.println("Sea Animals Types: " + Arrays.toString(SeaAnimalsTypes));
    }
}

//Main Class
//The Polymorphism happen here
class Polymorphism {
    public static void main(String[] args) {
        Animal AN = new Animal();
        AN.Landanimals();
        AN.Seaanimals();
    }
}
