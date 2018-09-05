# Podspecs

For use MUST be added the URL of a specs repository into Podfile for specifying location of pods

```ruby
source 'https://github.com/Viveron/Podspecs'
source 'https://github.com/CocoaPods/Specs.git'
```

Or specifyed the source for a particular pod
```ruby
pod 'NAME_OF_POD', :source => 'https://github.com/Viveron/Podspecs'
```
## Updation

For updation pod or adding new should perform command in terminal

```bash
pod repo push https://github.com/Viveron/Podspecs NAME.podspec
```
