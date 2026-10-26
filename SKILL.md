# micronaut.serde.api Skill

Use this skill to work with Norm module `micronaut.serde.api` version 6. Use only declarations listed below.

## `micronaut.serde.api`

Source: `Deserializer.norm`

### `Deserializer`

```norm
interface Deserializer<T>
```

Type parameters:

- `T`

## `micronaut.serde.api`

Source: `ObjectMapper.norm`

### `ObjectMapper`

```norm
interface ObjectMapper extends JsonMapper
```

#### `readValue`

```norm
T? readValue<T>(String? arg0, Class<T>? arg1)
```

Type parameters:

- `T`

Parameters:

- `arg0`: `String?`
- `arg1`: `Class<T>?`

Returns: `T?`

#### `writeValueAsString`

```norm
String? writeValueAsString(Any? arg0)
```

Parameters:

- `arg0`: `Any?`

Returns: `String?`

### `objectMapperGetDefault`

```norm
ObjectMapper? objectMapperGetDefault()
```

Returns: `ObjectMapper?`

## `micronaut.serde.api`

Source: `Serializer.norm`

### `Serializer`

```norm
interface Serializer<T>
```

Type parameters:

- `T`

## `micronaut.serde.api.annotation`

Source: `annotation/SerdeImport.norm`

### `SerdeImport`

```norm
annotation SerdeImport implements TypeTarget, RuntimeRetention, RepeatableAnnotation
```

#### `deserializable`

```norm
Boolean deserializable
```

Type: `Boolean`

#### `mixin`

```norm
Class<?> mixin
```

Type: `Class<?>`

#### `packageName`

```norm
String packageName
```

Type: `String`

#### `serializable`

```norm
Boolean serializable
```

Type: `Boolean`

#### `value`

```norm
Class<?> value
```

Type: `Class<?>`

#### `SerdeImport`

```norm
SerdeImport(Boolean? deserializable, Class<?>? mixin, String? packageName, Boolean? serializable, Class<?>? value)
```

Parameters:

- `deserializable`: `Boolean?`
- `mixin`: `Class<?>?`
- `packageName`: `String?`
- `serializable`: `Boolean?`
- `value`: `Class<?>?`

## `micronaut.serde.api.annotation`

Source: `annotation/Serdeable.norm`

### `Serdeable`

```norm
annotation Serdeable implements TypeTarget, RuntimeRetention
```

#### `naming`

```norm
Class<?> naming
```

Type: `Class<?>`

#### `validate`

```norm
Boolean validate
```

Type: `Boolean`

#### `Serdeable`

```norm
Serdeable(Class<?>? naming, Boolean? validate)
```

Parameters:

- `naming`: `Class<?>?`
- `validate`: `Boolean?`

## `micronaut.serde.api.annotation`

Source: `annotation/SerdeableDeserializable.norm`

### `SerdeableDeserializable`

```norm
annotation SerdeableDeserializable implements PackageTarget, TypeTarget, FieldTarget, ConstructorTarget, FunctionTarget, ParameterTarget, LocalTarget, RuntimeRetention
```

#### `asValue`

```norm
Class<?> asValue
```

Type: `Class<?>`

#### `naming`

```norm
Class<?> naming
```

Type: `Class<?>`

#### `using`

```norm
Class<?> using
```

Type: `Class<?>`

#### `validate`

```norm
Boolean validate
```

Type: `Boolean`

#### `SerdeableDeserializable`

```norm
SerdeableDeserializable(Class<?>? asValue, Class<?>? naming, Class<?>? using, Boolean? validate)
```

Parameters:

- `asValue`: `Class<?>?`
- `naming`: `Class<?>?`
- `using`: `Class<?>?`
- `validate`: `Boolean?`

## `micronaut.serde.api.annotation`

Source: `annotation/SerdeableSerializable.norm`

### `SerdeableSerializable`

```norm
annotation SerdeableSerializable implements PackageTarget, TypeTarget, FieldTarget, ConstructorTarget, FunctionTarget, ParameterTarget, LocalTarget, RuntimeRetention
```

#### `asValue`

```norm
Class<?> asValue
```

Type: `Class<?>`

#### `naming`

```norm
Class<?> naming
```

Type: `Class<?>`

#### `using`

```norm
Class<?> using
```

Type: `Class<?>`

#### `validate`

```norm
Boolean validate
```

Type: `Boolean`

#### `SerdeableSerializable`

```norm
SerdeableSerializable(Class<?>? asValue, Class<?>? naming, Class<?>? using, Boolean? validate)
```

Parameters:

- `asValue`: `Class<?>?`
- `naming`: `Class<?>?`
- `using`: `Class<?>?`
- `validate`: `Boolean?`

## `micronaut.serde.api.config.naming`

Source: `config/naming/IdentityStrategy.norm`

### `IdentityStrategy`

```norm
class IdentityStrategy implements PropertyNamingStrategy
```

#### `IdentityStrategy`

```norm
IdentityStrategy(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `micronaut.serde.api.config.naming`

Source: `config/naming/PropertyNamingStrategy.norm`

### `PropertyNamingStrategy`

```norm
interface PropertyNamingStrategy
```

