## Podfile.lock not generated example

This `Podfile` and CocoaPods combination seems to not generate a `Podfile.lock`
after running the install command.

To reproduce:

1. Checkout this repo
2. Run `bundle install`
3. Run `bundle exec pod install`

On my machine, no `Podfile.lock` is generated.

![screenshot of my terminal not generating the lock file](./screenshot.png)
