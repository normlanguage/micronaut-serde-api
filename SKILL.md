# micronaut.serde.api Skill

Use this skill to work with Norm module `micronaut.serde.api` version 5. Use only declarations listed below.

## `micronaut.serde.api`

### `Deserializer`

```norm
interface Deserializer<T>
```

## `micronaut.serde.api`

### `ObjectMapper`

```norm
interface ObjectMapper extends JsonMapper
```

#### `readValue`

```norm
T? readValue<T>(String? arg0, Class<T>? arg1)
```

#### `writeValueAsString`

```norm
String? writeValueAsString(Any? arg0)
```

### `objectMapperGetDefault`

```norm
ObjectMapper? objectMapperGetDefault()
```

## `micronaut.serde.api`

### `Serializer`

```norm
interface Serializer<T>
```

## `micronaut.serde.api.annotation`

### `SerdeImport`

```norm
annotation SerdeImport implements TypeTarget, RuntimeRetention, RepeatableAnnotation
```

#### `deserializable`

```norm
Boolean deserializable
```

#### `mixin`

```norm
Class<?> mixin
```

#### `packageName`

```norm
String packageName
```

#### `serializable`

```norm
Boolean serializable
```

#### `value`

```norm
Class<?> value
```

#### `SerdeImport`

```norm
SerdeImport(Boolean? deserializable, Class<?>? mixin, String? packageName, Boolean? serializable, Class<?>? value)
```

## `micronaut.serde.api.annotation`

### `Serdeable`

```norm
annotation Serdeable implements TypeTarget, RuntimeRetention
```

#### `naming`

```norm
Class<?> naming
```

#### `validate`

```norm
Boolean validate
```

#### `Serdeable`

```norm
Serdeable(Class<?>? naming, Boolean? validate)
```

## `micronaut.serde.api.annotation`

### `SerdeableDeserializable`

```norm
annotation SerdeableDeserializable implements PackageTarget, TypeTarget, FieldTarget, ConstructorTarget, FunctionTarget, ParameterTarget, LocalTarget, RuntimeRetention
```

#### `asValue`

```norm
Class<?> asValue
```

#### `naming`

```norm
Class<?> naming
```

#### `using`

```norm
Class<?> using
```

#### `validate`

```norm
Boolean validate
```

#### `SerdeableDeserializable`

```norm
SerdeableDeserializable(Class<?>? asValue, Class<?>? naming, Class<?>? using, Boolean? validate)
```

## `micronaut.serde.api.annotation`

### `SerdeableSerializable`

```norm
annotation SerdeableSerializable implements PackageTarget, TypeTarget, FieldTarget, ConstructorTarget, FunctionTarget, ParameterTarget, LocalTarget, RuntimeRetention
```

#### `asValue`

```norm
Class<?> asValue
```

#### `naming`

```norm
Class<?> naming
```

#### `using`

```norm
Class<?> using
```

#### `validate`

```norm
Boolean validate
```

#### `SerdeableSerializable`

```norm
SerdeableSerializable(Class<?>? asValue, Class<?>? naming, Class<?>? using, Boolean? validate)
```

## `micronaut.serde.api.config.naming`

### `IdentityStrategy`

```norm
class IdentityStrategy implements PropertyNamingStrategy
```

#### `IdentityStrategy`

```norm
IdentityStrategy(__JarBindingToken token)
```

