# custom_radio_grouped_button

Custom Radio Buttons and Grouped Check Box Button

Custom Flutter widgets that makes Checkbox and Radio Buttons much cleaner and easier.

## Installing

Add the following to your `pubspec.yaml` file:

    dependencies:
      custom_radio_grouped_button: any

# Creating Radio Button

    CustomRadioButton(
    buttonColor: Theme.of(context).canvasColor,
    buttonLables: [
       "Student",
       "Parent/Teacher",
      ],
    buttonValues: [
       "STUDENT",
       "TEACHER",
      ],
    radioButtonValue: (value) => print(value),
    selectedColor: Theme.of(context).accentColor,
    );

# Creating Grouped Button

    CustomCheckBoxGroup(
    buttonColor: Theme.of(context).canvasColor,
    buttonLables: [
      "Monday",
      "Tuesday",
      "Wednesday",
      "Thursday",
    ],
    buttonValuesList: [
      "Monday",
      "Tuesday",
      "Wednesday",
      "Thursday",
    ],
    checkBoxButtonValues: (values) => print(values),
    defaultSelected: "Monday",
    horizontal: true,
    width: 120,
    selectedColor: Theme.o.accentColor,
    padding: 5,
    );

## Screenshots

<img src="Screenshots/GroupButton.gif" alt="Grouped Button"/>

<img src="Screenshots/RadioButton.gif" alt="Grouped Button"/>