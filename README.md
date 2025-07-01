
# Инструмент для вставки видеоплеера

Данный репозиторий представлет собой видеоплеер, готовый для вставки в код.

![max example](./screenshots/screenshot.png)

Построен на базе библиотеки [Playable](https://wix.github.io/playable/).

Пример работы плеера можно просмотреть [Здесь](https://dmitriy877.github.io/Videoplayer/) на GitHub Pages

## Как подключить

Этот инструмент добавит на страницу плеер, который играет видео по [этой ссылке](https://dvmn.org/media/filer_public/78/db/78db3456-3fd3-4504-9ed9-d2d1fd843c0b/highest_peak.mp4).

Если хочется выбрать другое видео, с помощью аргумента `src` плееру можно указать какое видео проигрывать, ссылки обязаны заканчиваться расширением файла:

```html
<script type="text/javascript">
  createPlayer({
    elementId: 'player',
    src: 'https://dvmn.org/media/filer_public/d0/16/d016d9b8-4180-4bb9-ad83-0241f61627b8/samsung_demo_-_alive_in_color.mp4'
});
</script>
```

**Скрипт `player.js` нужно подключать строго после `<div>` с указанным elementId**

## Цели проекта

Код написан в учебных целях — [Devman](https://dvmn.org).
