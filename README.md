# Victory Native

### Usage

Install victory-native:
```sh
$ npm install victory-native --save
```

Install react-native-svg:
```sh
$ npm install react-native-svg --save
```

Link react-native:
```sh
$ react-native link react-native-svg
```
**`victory-native@^30.0.0` requires `react-native-svg@6.1.x`or `react-native-svg@^6.5.0`**

**Please see [Peer Dependencies and Version Requirements](#peer-dependencies-and-version-requirements) for requirements for previous versions of `victory-native`**


Import charts from `victory-native`. For example,

```jsx
import React, { Component } from "react";

import { VictoryBar } from "victory-native";

class App extends Component {
  render() {
    return (
      <VictoryBar />
    );
  }
}

export default App;
```

### Peer Dependencies and Version Requirements

**Note:** `victory-native` requires the following peer dependencies:
  - `react-native-svg`
  - `react`
  - `react-native`

**Note:** `react-native-svg` has strict version requirements for both `react` and `react-native`. Please match versions to those required by `react-native-svg`. See the up-to-date requirements on the [react-native-svg Readme][react-native-svg-readme].
We encourage you to use the latest version of `react-native-svg` possible for your project, as `victory-native` issues are frequently solved by `react-native-svg` bugfixes.

* `victory-native@^30.0.0` requires `react-native-svg@6.1.x` or `react-native-svg@^6.5.0`
* `victory-native@^0.16.2` requires `react-native-svg@6.1.x` or `react-native-svg@^6.5.0`
* ~~`victory-native@~0.16.0` requires `react-native-svg@6.0.0`~~ No longer supported
* ~~`victory-native@~0.15.0` requires `react-native-svg@^5.0.0`~~ No longer supported

### Local Development and Demo

If you'd like to contribute to `victory-native`, you can use the local demo app to test your changes on the iOS simulator. (But if you're just getting started with `victory-native` and want to see a demo, we recommend using [victory-native-demo][victory-native-demo], as it supports Android and is simpler to set up.)

```sh
# Install
$ git clone https://github.com/FormidableLabs/victory-native
$ cd victory-native
$ npm install
$ cd demo
$ npm install

# Run the demo from a new terminal window
$ npx react-native run-ios
```

Changes to `lib` will be reflected in the demo app.

### Documentation

See the docs and examples on the website https://formidable.com/open-source/victory/docs/native

## Contributor Covenant Code of Conduct

Please review our [Code of Conduct][code] before contributing.

[code]: https://github.com/FormidableLabs/builder-victory-component/blob/master/CONTRIBUTING.md#contributor-covenant-code-of-conduct
[victory-native-demo]:https://github.com/FormidableLabs/victory-native-demo
[react-native-svg-readme]: https://github.com/react-native-community/react-native-svg#notice
