# Script types
## TaskScript
## AbstractScript

# NPCs
`org.dreambot.api.methods.interactive.NPCs` https://dreambot.org/javadocs/3/org/dreambot/api/methods/interactive/NPCs.html

## Interact with an NPC
```java
import org.dreambot.api.methods.interactive.NPCs;
import org.dreambot.api.wrappers.interactive.NPC;

public class Main(){
    public Main(){
        NPC npc = NPCs.closest("NCP Name");
        npc.interact();
    }
}
```

# Keyboard
## Typing
```java
import org.dreambot.api.methods.input.Keyboard;

public class Main(){
    public Main(){
        Keyboard.type("Hello world!"); // This will press enter after typing
        Keyboard.type("Hello world!", false); // This will not press enter.
    }
}
```

# Logging
## Logging from class inheriting from MethodProvider
```java
import org.dreambot.api.script.AbstractScript;

public class Main extends AbstractScript {
    public Main(){
        log("Hello World!");
    }
}
```

## Logging from non extended class
```java

```