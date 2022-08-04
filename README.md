# PickerLocalizationDemo

PickerLocalizationDemo is an example demonstrating an issue with UIPickerView spinners and localization.
When the app is installed in one language and the user then switches languages on the phone, most localized
text is switched to the current language. However, the text of options in UIPickerViews is not.
If the app is completely removed from the phone and then reinstalled in the current language, the UIPickerView
text is displayed in the current language as expected.
