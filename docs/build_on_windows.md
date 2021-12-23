# Build on Windows

## Set Up WSLg
Develop on Linux and Windows at the Same Time for Instruction follow this [guide](https://gist.github.com/goldcoders/e9d572f005352fc4568482e5fad60a26)

## Development
1. Clone Repo

clone via ssh key

`git clone git@github.com:goldcoders/jigglepot.git`

or

clone via https

`git clone https://github.com/goldcoders/jigglepot.git`

2. Install Compative Flutter Version

```
fvm install 2.8.1
fvm use
```

2. Install Dependencies
```
flutter clean
flutter pub get
```


3. Run Build runner
```
dart run build_runner build
```

## Release on Windows

- Copy 3 Files on dll_lib
```
| ->  msvcp140.dll
| -> vcruntime140.dll
| -> vcruntime140_1.dll
```