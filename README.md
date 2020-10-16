# Popover

A description of this package.

因项目的需要 对iSapozhnik [Popover](https://github.com/iSapozhnik/Popover) 进行细微的修改， 感谢[https://github.com/iSapozhnik/Popover](https://github.com/iSapozhnik/Popover)

使用方法 和 https://github.com/shibiao/Popover 里swift packages一样，
新添加了对已存在的NSStatusItem的嵌入方法 ,而非由Popover底层创建

` public func prepare(with statusItem: NSStatusItem, contentViewController viewController: NSViewController) `

# Install

Since this is a Swift Package, the installation process is pretty stright forward.

### Manual way
Update your `Package.swift` dependencies:

```
dependencies: [
    .package(url: "https://github.com/shibiao/Popover", from: "1.4.0")
]
```

### Via Xcode:
1. Go to `File -> Swift Packages -> Add Package Dependency`. 
2. Put GitHub URL `https://github.com/shibiao/Popover` and click `Next`
3. Select the latest version
4. Click `Finish`
