# Prokatavto — Public Files

PDF-файлы (прайсы и образцы договоров) для скачивания со страниц «Юр. лицам»
сайтов [prokatavto67.ru](https://prokatavto67.ru) и [prokatavto32.ru](https://prokatavto32.ru).

Размещаются через GitHub Pages. После включения Pages файлы доступны по URL вида:

```
https://<username>.github.io/<repo>/price-smolensk.pdf
https://<username>.github.io/<repo>/contract-smolensk.pdf
https://<username>.github.io/<repo>/price-bryansk.pdf
https://<username>.github.io/<repo>/contract-bryansk.pdf
```

## Как обновить прайс

1. Положить новый PDF в эту папку под тем же именем (`price-smolensk.pdf` и т.д.)
2. `git add . && git commit -m "update price" && git push`
3. GitHub Pages обновит файл через ~1 минуту. URL остаётся прежним — на сайте Тильды ничего менять не нужно.
