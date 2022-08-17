# 🐇🕳 Rabbit Hole 
Collection containing many utils packages useful  with Swift development.

# 🏗 Installation

## Xcode

### Using menu tap to add packages:

`Xcode -> File -> Add Packages... -> Add Package Collection...` 

![AddPackage](https://github.com/sloik/RabbitHole/blob/main/img/rabbit-01.png?raw=true)

### Enter url containing `json` with packages in the collection:

`https://raw.githubusercontent.com/sloik/RabbitHole/main/collection.json` 

![Enter collection url](https://github.com/sloik/RabbitHole/blob/main/img/rabbit-02.png?raw=true)

Collection is not signed, but you can trust me 😇

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

# 🗑 Removal

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
Rename the file to `collection.json` and you are done 😎

# Structure

```
┌───────────┐┌───────────┐┌──────────┐┌─────────────┐┌──────────────┐
│[Major.Mino││  [Alias   ││[Optional ││   [Zippy]   ││ [Functional  │
│ r.Patch]  ││Wonderland]││   API]   ││             ││     API]     │
│           ││           ││          ││  Zips for   ││              │
│ Semantic  ││  Common   ││ Helpers  ││  types and  ││Free functions│
│Versioning:││vocabulary ││for Swift ││    async    ││and operators │
│semver.org ││ for other ││Optionals.││ functions.  ││ for function │
│           ││ packages. ││          ││             ││ composition. │
│           ││           ││          │└─────────────┘└──────────────┘
│           ││           ││          │┌─────────────────────────────┐
│           ││           ││          ││       [Either Swift]        │
│           ││           ││          ││                             │
│           ││           ││          ││Implementation for the Either│
└───────────┘└───────────┘└──────────┘└─────────────────────────────┘
```
