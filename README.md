# [Go back to Overview](https://github.com/c4arl0s)

In order to update an existing Git submodule execute (You migh need permissions from Owner)

```console
 git submodule update --remote --merge
```

# Using AI to understand project:

### Describe briefly how to understand SwuifUI paradigm programming language

SwiftUI is a declarative framework for building user interfaces on Apple platforms.Instead of describing step-by-step how the UI should change (imperative), you declare what the UI should look like for a given state. When the state changes, SwiftUI automatically updates the UI to match.

Key concepts:
- **Declarative Syntax**: You describe the UI by declaring views and their relationships, not by writing code to update them manually.
- **State-driven**: The UI is a function of your app’s state. When the state changes, the UI updates automatically.
- **Composable Views**: Complex interfaces are built by combining small, reusable view components.
- **Reactive**: Uses property wrappers like @State, @Binding, and @ObservedObject to react to data changes.

Example:

```swift
@State private var isOn = false

var body: some View {
    Toggle("Enable Feature", isOn: $isOn)
    if isOn {
        Text("Feature is enabled!")
    }
}
```

Summary:

SwiftUI is about declaring what you want the UI to be for a given state, letting the framework handle the updates, and composing interfaces from small, reusable pieces. This leads to simpler, more maintainable code compared to traditional imperative UI frameworks.

# 1. [Introducing SwiftUI](https://github.com/c4arl0s/IntroducingSwiftUI#go-back-to-overview)

1. [x] [Creating and Combining Views](https://github.com/c4arl0s/CreatingAndCombiningViews#creating-and-combining-views---content)
2. [x] [Building List and Navigation](https://github.com/c4arl0s/BuildingListAndNavigation#building-list-and-navigation---content)
3. [x] [handling User Input](https://github.com/c4arl0s/HandlingUserInput#handling-user-input---content)

# 2. Drawing and Animation

1. [ ] [Drawing Paths and Shapes](https://github.com/c4arl0s/DrawingPathsAndShapes#drawing-paths-and-shapes---content)
2. [ ] [Animating Views and Transitions](https://github.com/c4arl0s/AnimatingViewsAndTransitions#animating-views-and-transitions---content)

# 3. App Design and Layout

1. [ ] [Composing Complex Interfaces](https://github.com/c4arl0s/ComposingComplexInterfaces#composing-complex-interfaces---content)
2. [ ] [Working with UI Controls](https://github.com/c4arl0s/WorkingWithUIControls#working-with-ui-controls---content)

# 4. Framework Integration

1. [ ] [Interfacing with UIKit](https://github.com/c4arl0s/InterfacingWithUIKit#interfacing-with-uikit---content)
2. [ ] [Creating a watchOS App](https://github.com/c4arl0s/CreatingAWatchOSApp#creating-a-watchos-app---content)
3. [ ] [Creating a macOS App](https://github.com/c4arl0s/CreatingAmacOSApp#creating-a-macos-app---content)

# 5. Resources

1. Documentation
2. Videos
3. Forums
4. Sample Code
5. Xcode and SDKs
