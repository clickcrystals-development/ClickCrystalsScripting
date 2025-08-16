[<-- Back to Legend](../legend.md)

# Command Name: Interact
Keyword: interact

### Usages
```
interact any_block
interact any_entity
interact nearest_block <identifier>
interact nearest_entity <identifier>
interact position <x> <y> <z>
interact target_entity
```

### Regex
```regexp
(((interact)( (nearest_entity|nearest_block))( !?(([#:](\w+)(\[(.*)\])?,?)+)))|((interact)( (any_entity|target_entity|any_block)))|((interact)( (position))( ([\^~]?-?\d*(\.\d*)?))( ([\^~]?-?\d*(\.\d*)?))( ([\^~]?-?\d*(\.\d*)?))))
```

### Raw Documentation
```yml
# interact (nearest_entity|nearest_block) <identifier>
# interact (any_entity|target_entity|any_block)
# interact position <x> <y> <z>
```
