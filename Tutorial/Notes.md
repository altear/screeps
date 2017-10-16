# Tutorial Notes
Resource Managment
## Creeps
### Storing Creep Memory
### Deleting Creeps
Creeps can be deleted using their suicide function:
`Game.creeps[creep].suicide();`
Creep memory persists after its deletion (suicide). To delete the memory:
`delete Memory.creeps[name];`

