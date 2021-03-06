---
-api-id: M:Windows.Globalization.NumberFormatting.PercentFormatter.#ctor(Windows.Foundation.Collections.IIterable{System.String},System.String)
-api-type: winrt method
---

<!-- Method syntax
public PercentFormatter(Windows.Foundation.Collections.IIterable<System.String> languages, System.String geographicRegion)
-->

# Windows.Globalization.NumberFormatting.PercentFormatter.PercentFormatter

## -description
Creates a [PercentFormatter](percentformatter.md) object initialized by a language list and a geographic region.

## -parameters
### -param languages
The list of language identifiers, in priority order, representing the choice of languages. See Remarks.

### -param geographicRegion
The identifier for the geographic region.

## -remarks
If your app passes language tags used in this class to any [National Language Support](http://msdn.microsoft.com/library/7a548074-0782-45e1-8051-80c3b9d81885) functions, it must first convert the tags by calling [ResolveLocaleName](http://msdn.microsoft.com/library/99264b22-3fb5-47e2-b0b9-42a6768e67c1).

**Starting in :** Language tags support the Unicode extensions "ca-" and "nu-". (See [Unicode Key/Type Definitions](http://go.microsoft.com/fwlink/p/?LinkId=308919).) Note that the "nu-" extension can affect the numeral system used by [PercentFormatter](percentformatter.md) objects.

## -examples

## -see-also
[Unicode Key/Type Definitions](http://go.microsoft.com/fwlink/p/?LinkId=308919)