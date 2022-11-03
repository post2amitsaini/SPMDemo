# SPMDemo
Swift Package Manager tutorial and creating your own SPM

First open Xcode and select new project with option Swift Package

 ![SPM_1](https://user-images.githubusercontent.com/43773429/199739722-51f66064-5f7f-4304-bb0c-d51de4398ed2.png)

Once Package is created, You see Package.swift file


![SPM_2](https://user-images.githubusercontent.com/43773429/199742842-10de68d4-1aa9-41bd-8b58-1dca6929d6a5.png)


First line is:
 // swift-tools-version:5.5

Here 5.5 is Swift version, Line is commented but if you change the version, Package will update and add/remove dependencies accordingly.

second here is  name: "SPMDemo", means Package manager name


 Third   dependencies: [
        // Dependencies declare other packages that this package depends on.
        // .package(url: /* package url */, from: "1.0.0"),
    ]

Here you can add dependencies if your SPM has and same has to update in Target

.target(
            name: "SPMDemo",
            dependencies: [Here you have to add])
