#Game Algorithm

##Receiving input

### Define variables

### Setup method

1. write the desired association between keys and actions (mappping)  

2. define input listeners setting events (from mouse and key board)

### Bind method

1. Create a map, associating the desired command keys (defined by the user) and action.


### Events methods

#### onMouseMove

1. Retrieve client mouse positions, x and y

#### onKeyDown

1. Retrieve keyCode
2. Using it, retrieve from the set map the respective action
3. If the key pressed correspond to a action, verify it using a conditional verification.

- if the the correspondence exits, set the action value, true

#### onKeyUp

1. Existing the action, when the key is released set the action value false. 
