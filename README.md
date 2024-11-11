## How to use?

- Install the package
- Use it by calling the `CopyableTextInput` class just like a normal `TextInput` class and call `->copyable()` method to
  make it copyable.
- You can use all others methods from default `TextInput` class like `->label()`, `->placeholder()`, `->readOnly()`,
  etc.

```php
use Digiage\CopyableTextInput\CopyableTextInput;

CopyableTextInput::make('invoice_number')
                  ->label('Invoice Number')
                  ->placeholder('Invoice number is auto generated')
                  ->readOnly()
                  ->copyable()
```
