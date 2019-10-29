# AGIntroduceViewController
It's an introduce view controller for images.

## Install
```ruby
use_frameworks!
pod 'AGIntroduceViewController-Objc', :git => "https://github.com/Bomiishere/AGIntroduceViewController.git"
```
```ruby
pod install
```

## Usage
```ruby
 IntroduceViewController *vc = [[IntroduceViewController alloc] initWithImages:images];
 [vc setBackgroundColor:[UIColor whiteColor]];
 [vc setPageControlSelectedColor:[UIColor darkGrayColor]];
 vc.isLastPageShowDoneButton = YES;
 vc.endBlock = ^{
    [self doSomething];
 };
```

## Environment
* iOS: 11.0
* language: Objective-C
