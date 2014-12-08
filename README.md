# Banyan

## Collaborative social experiences

This is a product being built by the Assembly community. You can help push this idea forward by visiting [https://assembly.com/banyan](https://assembly.com/banyan).

### Getting started

This repo is for iPhone app of [Banyan](www.banyan.io).

To start contributing to this project:

1. Clone this repository
2. Install [cocoapods](http://guides.cocoapods.org/using/getting-started.html)
3. `pod install` at the command prompt
4. Type *open Banyan.xcworkspace* at the command prompt
5. Update the required credentials in *BanyanAppDelegate.h* and add Facebook app info in *Banyan-Info.plist*
6. Build and run

It is recommended that you start your own development server using the [backend repository](https://github.com/asm-products/banyan-web) and make sure that when the iOS app is running, it connects at *http://127.0.0.1:8000/api/v1/*. This is configurable in the *Networking Extensions/AFBanyanAPIClient.m* file.
