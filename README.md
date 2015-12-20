# Processwire Language Locales
This module adds new properties to *language* template
related to locale info.

## Example Usage

```php
<?php 

echo '<ul>';

foreach ($languages as $language):

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

**Output**

```
es-CL
es_CL
es
Español (Chile)
Español
Chile
CL
```