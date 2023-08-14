## Sandbox

For the first time, world will be a simple fixed size box where
going beyond the borders is prohibited (or death)

World class contains all alive and non-alive objects on the map.
All alive NPCs are divided into categories of same type.
For now, same type of species will have same NN running theirs behaviour.


Let all sandbox have not only physical world map, but also a map of
vibrations in sand. Vibrations will be represented as a vector field.

- each tick field is moving according to it's vectors.
- each send square creates a little vibration
- each step on the ground - creates medium vibration
- each worm movement creates strong vibration

