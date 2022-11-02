Provides a custom [TypeAhead](https://pub.dev/packages/flutter_typeahead) bindable with a **single selective** or **multi selective** item list. Multiple selections, can be shown as id based **chips**.

## Usage

```dart
final List<DgstSelectionItem> initItems = <DgstSelectionItem>[
    const DgstSelectionItem(id: 1, name: 'Item 1'),
    const DgstSelectionItem(id: 2, name: 'Item 2')
];
```

```dart
DgstSelector(
    title: 'Multi-Selector',
    dgstSelectorType: DgstSelectorType.MULTI_SELECTOR,
    sourceCallback: testCallback(),
    initialSelectedItems: initItems,
    onSelectedItemsChanged: (value) => print(' > Selected Items Changed < : $value'),
)
```

![Output](https://filebin.net/3933v2r4zq0m5ux6/output.gif)

---

Any contributions will be appreciated.
