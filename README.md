
# react-native-draggable-trello

## Getting started

`$ npm install react-native-draggable-trello --save`

### Mostly automatic installation

`$ react-native link react-native-draggable-trello`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-draggable-trello` and add `RNDraggableTrello.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNDraggableTrello.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNDraggableTrelloPackage;` to the imports at the top of the file
  - Add `new RNDraggableTrelloPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-draggable-trello'
  	project(':react-native-draggable-trello').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-draggable-trello/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-draggable-trello')
  	```

#### Windows
[Read it! :D](https://github.com/ReactWindows/react-native)

1. In Visual Studio add the `RNDraggableTrello.sln` in `node_modules/react-native-draggable-trello/windows/RNDraggableTrello.sln` folder to their solution, reference from their app.
2. Open up your `MainPage.cs` app
  - Add `using Draggable.Trello.RNDraggableTrello;` to the usings at the top of the file
  - Add `new RNDraggableTrelloPackage()` to the `List<IReactPackage>` returned by the `Packages` method


## Usage
```javascript
import RNDraggableTrello from 'react-native-draggable-trello';

// TODO: What to do with the module?
RNDraggableTrello;
```
  