# LOHTutorial
About iOS app development

* Application Life Cycle
    - UIKit App Delegate
    - SwiftUI App

* Layout
    - Manual layout
        * override `layoutSubviews`
    - Autoresizing (the oldest way)
        * autoresizingMask (struts and spring)
    - Autolayout
        * constraints (based on `layoutSubviews`)

Autoresizing是默认的布局方式，如果我们用代码的方式创建用autolayout的view，我们应该主动将autoresizing 禁止。而最新的基于`.storyboard`和`.xib`的view都用的是`autolayout`。

Books

* [Programming iOS 13: Dive Deep into Views, View Controllers, and Frameworks](https://www.amazon.com/Programming-iOS-13-Controllers-Frameworks/dp/1492074616)

Blogs

* [wwdcbysundell](https://wwdcbysundell.com/)

See more [Wiki](https://github.com/LockedOutofHeaven/LOHTutorial/wiki)