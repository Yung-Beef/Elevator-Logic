Build an configurable elevator logic program ready for release and put it on crates.io

Allow configs for:
- Multiple number and types of elevators (different types can have different speeds)
- Number of floors
- Logic for whether they hold position or try to sit in the middle of the building etc.
- Implement with traits (use supertraits?)
- Use generics so other people can create new elevator types
- Use cryptography so only valid users can use the elevator (optional)
- Multiple threads for different elevators
- If #1 is already coming down but #2 is closer and I'm at the bottom and hit the up button, which elevator comes?