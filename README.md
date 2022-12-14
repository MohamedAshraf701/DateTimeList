## Platform Support | Android | iOS | | :-----: | :-: | | ✔️ | ✔️

## Features

Flutter Date Picker Library that provides a calendar as a horizontal timeline.


## Imports


```dart 

 import 'package:datetimelist/date_picker_timeline.dart';
 
```

## Usage

```dart 

  DatePicker(
        DateTime.now(),
        initialSelectedDate: DateTime.now(),
        selectionColor: Colors.black,
        selectedTextColor: Colors.white,
        onDateChange: (date) {
          // New date selected
          setState(() {
            _selectedValue = date;
          });
        },
      ),
 
```




## Constructor


```dart 
DatePicker(
    this.startDate, {
    Key key,
    this.width,
    this.height,
    this.controller,
    this.monthTextStyle,
    this.dayTextStyle,
    this.dateTextStyle,
    this.selectedTextColor,
    this.selectionColor,
    this.deactivatedColor,
    this.initialSelectedDate,
    this.activeDates,
    this.inactiveDates,
    this.daysCount,
    this.onDateChange,
    this.locale = "en_US",
}) : super(key: key);

```