# BracketsIDE

### Настройка путей к PHP, и перетаскивание текста

Открыть brackets.json (Debug > Open Preferences File) и отредактировать в соответствии с кодом ниже.

```sh
{
    "brackets-eslint.gutterMarks": true,
    "brackets-eslint.useLocalESLint": false,
    "fonts.fontSize": "17px",
    "dragDropText": true,
    "fonts.fontFamily": "'SourceCodePro-Medium', ＭＳ ゴシック, 'MS Gothic', monospace",
    "themes.theme": "dark-theme",
    "php": {
        "enablePhpTooling": true, 
	"executablePath": "D:\\WORK\\OSPanel\\modules\\php\\PHP_7.3\\php.exe",
	"memoryLimit": "4095M", 
	"validateOnType": "false" 
}
}
```

### Установка необходимых пакетов

* Emmet
* PHP SmartHints
* PHP Code Quality Tools
* Overscroll
* Quick Search
* CSS Color Preview (View->Enable css color preview)
* Indent Guides (View->Indent Guides)
