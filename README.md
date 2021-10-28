# Chosen

Stellt eine einfache Bibliothek jQuery Chosen zur Verfügung für die weitere, individuelle Implementierung via Javascript zur Verfügung.

https://github.com/harvesthq/chosen-package


**Einbindung**
```
<link  href="/assets/trilobit-chosen/dist/chosen.min.css" rel="stylesheet">
<script src="/assets/trilobit-chosen/dist/chosen.jquery.min.js"></script>
```
oder via `$GLOBALS`:
```
$GLOBALS['TL_CSS'][] = 'assets/trilobit-chosen/dist/chosen.min.css|static';
$GLOBALS['TL_JAVASCRIPT'][] = 'assets/trilobit-chosen/dist/chosen.jquery.min.js|static';
```

**Verwendung**
```
<select data-placeholder="Choose a country..." multiple class="chosen-select">
<script>
  $(".chosen-select").chosen();
</script>
```

**ergänzende Infos**
sind in der README.md unter `/assets/trilobit-datepicker/dist/README.md` oder hier (https://harvesthq.github.io/chosen/) zu finden.