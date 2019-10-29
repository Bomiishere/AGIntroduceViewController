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
 [vc setBackgroundColor:[UIColor colorWithRed:239/255.f green:188/255.f blue:18/255.f alpha:1.0]];
 [vc setPageControlSelectedColor:[UIColor darkGrayColor]];
 vc.isLastPageShowDoneButton = YES;
 vc.endBlock = ^{
    [self changeRootViewToTabVC];
 };
```

## Environment
* iOS: 11.0
* language: Objective-C
