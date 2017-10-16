# Tutorial Notes
## Defense
Towers and Creeps can be used to defend base. Walls can keep out intruders for a time, and safe mode can prevent further attacks.
Attacks can damage buildings, in which case repairs can be made.

## Creeps
### Storing Creep Memory
Creeps can store information about themselves in their memory
`creep.memory.speech = "Hello World";`
### 
### Deleting Creeps
Creeps can be deleted using their suicide function:
`Game.creeps[creep].suicide();`
Creep memory persists after its deletion (suicide). To delete the memory:
`delete Memory.creeps[name];`

