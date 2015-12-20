# Processwire Language Locales
This module adds the following properties to *language* template.

## Example Usage

```php
<?php 
echo '<ul>';

foreach ($languages as $language):

echo "<li>{$language->template}</li>";
echo "<li>{$language->name}</li>";
echo "<li>{$language->title}</li>";
echo "<li>{$language->locale}</li>";
echo "<li>{$language->localeUnderscore}</li>";
echo "<li>{$language->localeCode}</li>";
echo "<li>{$language->localeName}</li>";
echo "<li>{$language->localeLanguageName}</li>";
echo "<li>{$language->localeCountry}</li>";
echo "<li>{$language->localeCountryCode}</li>";

endforeach; 

echo '</ul>';
```
