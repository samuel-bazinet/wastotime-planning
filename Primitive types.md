The main issue here is how to handle the primitive types. If I want to add serialization or equality modifiers, I may need to manually create a representation of these types. I could also maintain a list of primitive types and hard code some logic for them. I'll have to take whichever option is more intuitive.

After some thought, it may be easier to list out all the primitive types (ints, floats, and string), then use the frontend to connect the dots and assume that everything will be fine.
