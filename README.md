# ππ³ Rabbit Hole 
Collection containing many utils packages useful  with Swift development.

# π Installation

## Xcode

### Using menu tap to add packages:

`Xcode -> File -> Add Packages... -> Add Package Collection...` 

![AddPackage](https://github.com/sloik/RabbitHole/blob/main/img/rabbit-01.png?raw=true)

### Enter url containing `json` with packages in the collection:

`https://raw.githubusercontent.com/sloik/RabbitHole/main/collection.json` 

![Enter collection url](https://github.com/sloik/RabbitHole/blob/main/img/rabbit-02.png?raw=true)

Collection is not signed, but you can trust me π

### Marvel at the collection Xcode

![Added Collection](https://github.com/sloik/RabbitHole/blob/main/img/rabbit-03.png?raw=true)

## Terminal

Enter commands:

```bash
swift package-collection add --trust-unsigned https://raw.githubusercontent.com/sloik/RabbitHole/main/collection.json

swift package-collection refresh
``` 

### Marvel at the collection in Xcode

![Added Collection](https://github.com/sloik/RabbitHole/blob/main/img/rabbit-03.png?raw=true)

# π Removal

### Xcode

Follow steps to install but just select collection and tap minus button.

### Terminal

```bash
swift package-collection remove https://raw.githubusercontent.com/sloik/RabbitHole/main/collection.json
```

# Generation

Update `input.json` with desired packages and run:

```bash
package-collection-generate input.json ./output.json
```
Rename the file to `collection.json` and you are done π

# Structure

```
βββββββββββββββββββββββββββββββββββββββββββββββββββββββββββββββββββββ
β[Major.Minoββ  [Alias   ββ[Optional ββ   [Zippy]   ββ [Functional  β
β r.Patch]  ββWonderland]ββ   API]   ββ             ββ     API]     β
β           ββ           ββ          ββ  Zips for   ββ              β
β Semantic  ββ  Common   ββ Helpers  ββ  types and  ββFree functionsβ
βVersioning:ββvocabulary ββfor Swift ββ    async    ββand operators β
βsemver.org ββ for other ββOptionals.ββ functions.  ββ for function β
β           ββ packages. ββ          ββ             ββ composition. β
β           ββ           ββ          ββββββββββββββββββββββββββββββββ
β           ββ           ββ          ββββββββββββββββββββββββββββββββ
β           ββ           ββ          ββ       [Either Swift]        β
β           ββ           ββ          ββ                             β
β           ββ           ββ          ββImplementation for the Eitherβ
βββββββββββββββββββββββββββββββββββββββββββββββββββββββββββββββββββββ
```
