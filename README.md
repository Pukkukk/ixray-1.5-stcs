# IX-Ray

<div align="center">
  <p>
    <a href="https://github.com/ixray-team">
      <img src="https://github.com/ixray-team/ixray-artwork/blob/default/res/IX-Ray/VK%20splash.png" alt="IX-Ray Team" />
    </a>
  </p>
</div>  

Репозиторий стабильной версии модифицированного движка _X-Ray_ 1.5 для «Чистое Небо».

## Для сборки движка необходимо:

- Visual Studio 2022 Community Edition
  - MFC v14.35 (17.5)
  - C++/CLI V143 (14.35-17.5)
  - Windows SDK 10.0.19041.0

Для ориентирования можно опереться на файл с личной сборкой компонентов от автора: [Открыть](my_components.md)    

## Чтобы собрать, нужно:

- Склонировать репозиторий локально с помощью программы Git:

```console
git clone https://github.com/Pukkukk/ixray-1.5-stcs.git
```
- Либо в начальном окне Visual Studio 2022 нажать кнопку «Клонирование репозитория» и вставить ссылку ниже:

```console
https://github.com/Pukkukk/ixray-1.5-stcs.git
```

### Сборка:

- Открыть проект с помощью файла `XRay.Engine.slnf`, выбрать желаемую конфигурацию (`Debug`, `Mixed`, `Release`) и платформу `x86` и собрать решение (`Сборка > Собрать решение (F7)`).

## Лицензия

Просмотрите [данный](LICENSE.md) файл.