# React_Native_Starter_Kit

### React Native is a popular framework for building mobile applications using JavaScript and React. Below is a beginner cheat sheet for React Native that includes essential concepts, components, and commands that you will frequently use as a reference.

### Setting Up Environment
- Install Node.js and npm: Required to run the package and manage dependencies.
- Install the React Native CLI: npm install -g react-native-cli
- Install Expo CLI (optional, but simplifies development): npm install -g expo-cli

### Creating a New Project
- React Native CLI: react-native init ProjectName
- Expo CLI: expo init ProjectName

### Running Your Project
- With React Native CLI:
   - react-native run-ios for iOS.
   - react-native run-android for Android.
- With Expo:
  - expo start then press i for iOS or a for Android.
  - incase if it does not worked "--npm install -g expo-cli" and for running the CLI "expo-cli start --tunnel"
 

### Basic Components
- View: A container that supports layout with flexbox, style, some touch handling.
- Text: A component for displaying text.
- Image: A component for displaying images.
- ScrollView: Provides a scrolling container.
- StyleSheet: Provides an abstraction layer similar to CSS stylesheets.

### UI Components
- Button: A basic button component for handling touches.
- TextInput: To allow users to input text.
- Switch: A binary toggle switch component.
- ActivityIndicator: Displays a circular loading indicator.

### Navigation
- React Navigation:
- npm install @react-navigation/native
- For stack navigation: npm install @react-navigation/stack
- For bottom tabs: npm install @react-navigation/bottom-tabs
- For drawer: npm install @react-navigation/drawer

### Layout with Flexbox
- Flex Direction: row (default for web) or column (default for React Native).
- Justify Content: flex-start, center, flex-end, space-around, space-between.
- Align Items: flex-start, center, flex-end, stretch.

### Styling
- Inline styles: <View style={{ margin: 10, padding: 10 }} />
- StyleSheet creation: const styles = StyleSheet.create({ container: { ... } });

### Handling Touches
- Touchable Components: TouchableOpacity, TouchableHighlight, TouchableWithoutFeedback.
- Handling Press: <Button onPress={() => { /* handle press */ }} />

### State Management
- useState Hook: const [state, setState] = useState(initialState);
- Context API: Provide and consume data at different levels of the component tree.

### Lifecycle and Effects
- useEffect Hook: Runs side effects outside of the render method.

### Networking
- Fetch API: For network requests.
- Axios: A third-party library that can be used for HTTP requests.

### Debugging
- Console.log: For basic debugging.
- React Native Debugger: Standalone app for debugging React Native applications.

### Useful Commands
- Reload app: Double tap R on your keyboard or shake the device.
- Open developer menu: cmd + D for iOS simulators, cmd + M for Android emulators.

### Additional Libraries
- State Management: Redux, MobX.
- Forms: Formik, react-hook-form.
- Navigation: React Navigation, react-native-navigation.
- UI Toolkit: NativeBase, React Native Elements, React Native Paper.

### Publishing
- Expo: expo publish
- React Native CLI: Build the app using Xcode or Android Studio and follow the respective platform's guide to publishing.

