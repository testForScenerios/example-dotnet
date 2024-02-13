# [:] Example Dotnet Project - Trigger scan - try 15

An example dotnet project to demonstrate [srcclr](https://www.srcclr.com) scans.

## Try me!

For running scan install .NetFramework and msbuild 

### Windows

```
choco install srcclr
srcclr activate
git clone https://github.com/srcclr/example-dotnet
msbuild example-dotnet/
srcclr scan example-dotnet/
```

### OSX
```
brew tap srcclr/srcclr
brew install srcclr
srcclr activate
git clone https://github.com/srcclr/example-dotnet
msbuild example-dotnet/
srcclr scan example-dotnet/ test123456111
```
