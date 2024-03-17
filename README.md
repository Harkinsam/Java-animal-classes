# Animal Hierarchy

This Java project implements an animal hierarchy with classes `Animal`, `Dog`, and `Fish`. Each class represents specific characteristics and behaviors of animals.

## Animal Class

The `Animal` class serves as the base class for all animals and includes attributes such as name, brain size, body size, size, and weight. It also provides methods for eating and moving.

### Attributes

- `name`: Name of the animal.
- `brain`: Size of the brain.
- `body`: Size of the body.
- `size`: Overall size of the animal.
- `weight`: Weight of the animal.

### Methods

- `eat()`: Method to simulate eating behavior.
- `move(speed)`: Method to simulate movement at a specified speed.

## Dog Class

The `Dog` class extends the `Animal` class and includes specific attributes and methods for dogs, such as eyes, legs, tail, teeth, and coat. It also overrides the `eat()` and `move(speed)` methods.

### Attributes

- `eyes`: Number of eyes.
- `legs`: Number of legs.
- `tail`: Length of the tail.
- `teeth`: Number of teeth.
- `coat`: Type of coat (e.g., fur color).

### Methods

- `chew()`: Method to simulate chewing behavior.
- `walk()`: Method to simulate walking behavior.
- `run()`: Method to simulate running behavior.
- `moveLegs(speed)`: Method to simulate leg movement.
- `eat()`: Overridden method to simulate eating behavior for dogs.
- `move(speed)`: Overridden method to simulate movement at a specified speed for dogs.

## Fish Class

The `Fish` class extends the `Animal` class and includes specific attributes and methods for fish, such as gills, eyes, and fins. It also includes methods to simulate swimming behavior.

### Attributes

- `gills`: Number of gills.
- `eyes`: Number of eyes.
- `fins`: Number of fins.

### Methods

- `rest()`: Method to simulate rest behavior.
- `moveMuscles()`: Method to simulate muscle movement during swimming.
- `moveBackFin()`: Method to simulate back fin movement during swimming.
- `swim(speed)`: Method to simulate swimming behavior at a specified speed.

## Usage

In the `Main` class or any other appropriate class, you can create instances of `Animal`, `Dog`, and `Fish` classes and invoke their methods to demonstrate their behaviors.

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.
