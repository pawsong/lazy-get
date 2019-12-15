# lazy-get

decorator for getter lazy evaluation

## Example

```typescript
import lazy from 'lazy-get'

class MyModule {
  @lazy get field() {
    return {}
  }
}

const mod = new MyModule()
assert(mod.field === mod.field)
```

## License

MIT
