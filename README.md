# lazy-get

@lazy getter decorator

## Example

```typescript
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
