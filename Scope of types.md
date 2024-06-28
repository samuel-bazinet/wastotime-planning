In most systems, types are organized so that lower level types are stored in a different part of the code as the "main" types. This poses a challenge as I'll need to keep track of where types will end up and which type needs which other type and which import will be needed to connect the 2. 

## Potential solutions:
1. When creating `RawType`s, store the relative location of the type inside of the Type list. This can be used to confirm that the type exist and adds an early failure point if the user forgot to create all the sub types.