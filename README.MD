#Instagram viewer

An open source Instagram tags viewer for iOS.

####Features
- Minimal design.
- Infinite scroll.
- Parallax while scrolling.
- Saving and sharing.

<img src="res/snap.jpg" width=320>

--------------------
##Installation

- Requires [cocoa pods](https://cocoapods.org).
- Do a `pod install` in the root directory to update dependencies.
- Go to [Instagram developers](https://www.instagram.com/developer/) and request a client ID.
- Set your client ID in `InstagramV2ViewController.m`
- Build and run.

--------------------
##The app uses:

- [SDWebImage](https://github.com/rs/SDWebImage) for caching and async loading of images.
- [SVProgressHUD](https://github.com/SVProgressHUD/SVProgressHUD) as a clean and minimal heads up display. 
- [KWTransition](https://github.com/KurtWagner/KWTransition) for some view transistions.
- [DZNEmptyDataSet](https://github.com/dzenbot/DZNEmptyDataSet) to easily handle empty data sets.

--------------------
###Contribution
Feel free to send a pull request.