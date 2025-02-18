# Translations

Translating Homechart is an ongoing process.  You can help us out by [updating or adding translations](#update) or [contacting support](../getting-help/paid-support.md) with the language you want or corrected translations.

## Updating or Adding Translations {#update}

Homechart generates translations from the [translations.yaml](https://github.com/candiddev/homechart/blob/main/translations.yaml) file.  It's a big file, but it lets you see _everything_ there is to translate in Homechart.

### Syntax

The syntax for the file is easy to understand:

```yaml
defaultcode: en # English is the default/fallback language
iso639codes: # A list of the ISO-639 codes and the display name for them
  de: Deutsch
  en: English
translations: # A list of translation objects.  The objects contain context and a translation for each of the iso639codes
  EmailEmailAddressChangeConfirmationSubject:
    context: Subject for email address changes
    de: '[Aktion erforderlich] Bestätigen Sie Ihre aktualisierte E-Mail-Adresse'
    en: |
      [Action Required] Verify Your Updated Email Address
```

### Adding a new language

To add a new language, please contact us.  You can add it to the translations.yaml, but we have tooling that can generate the translations first and then have you review them.

### Updating translations

You can update the translations if you notice something in Homechart that isn't translated correctly.  Checkout this [git repo](https://github.com/candiddev/homechart) and open a pull request with your changes.  You should be able to search the document to find the original translation.

