# smiley_rating_dialog_pro

A new Flutter package which helps you to implement beautiful customizable Smiley Rating Dialog Pro in your app.

The source code is **100% Dart**, and everything resides in the [/lib](https://github.com/mohak1283/Smiley-Rating-Dialog/tree/master/lib) folder.

## Show some :heart: and star the repo to support the project

 [![GitHub followers](https://img.shields.io/github/followers/mohak1283.svg?style=social&label=Follow)](https://github.com/zee604) 

[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=102)](https://opensource.org/licenses/Apache-2.0)



## 💻 Installation

In the `dependencies:` section of your `pubspec.yaml`, add the following line:

```yaml
smiley_rating_dialog: <latest_version>
```

Import in your project:
```dart
import 'package:smiley_rating_dialog/smiley_rating_dialog.dart';
```

## **Usage**
```dart
class HomeScreen extends StatefulWidget {
  @override
  _HomeScreenState createState() => _HomeScreenState();
}

class _HomeScreenState extends State<HomeScreen> {
  @override
  Widget build(BuildContext context) {
    return Center(
      child: RaisedButton(
        onPressed: () {
          showDialog(
              barrierDismissible: true,
              context: context,
              builder: (context) => SmileyRatingDialog(
                    title: Text('Smiley Dialog'),
                    starColor: Colors.red,
                    isRoundedButtons: true,
                    positiveButtonText: 'Ok',
                    negativeButtonText: 'Cancel',
                    positiveButtonColor: Colors.amber,
                    negativeButtonColor: Colors.amber,
                    onCancelPressed: () => Navigator.pop(context),
                    onSubmitPressed: (rating) {},
                  ));
        },
        child: Text('Show Dialog'),
      ),
    );
  }
}
```
## Screenshots

![smiley_rating_dialog](https://user-images.githubusercontent.com/35039342/56470228-9ff8d180-6461-11e9-9d2d-5e48be3862b6.gif)


## 💰 Donations

This project needs you! If you would like to support this project's further development, the creator of this project or the continuous maintenance of this project, feel free to donate. Your donation is highly appreciated (and I love food, coffee and beer). Thank you!


# 👍 How to Contribute

1. Fork it
2. Create your feature branch (git checkout -b my-new-feature)
3. Commit your changes (git commit -am 'Add some feature')
4. Push to the branch (git push origin my-new-feature)
5. Create new Pull Request

# 📃 License

    Copyright (c) 2024 Zee604

    Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Getting Started

For help getting started with Flutter, view our online [documentation](https://flutter.dev/).

For help on editing package code, view the [documentation](https://flutter.dev/developing-packages/).

