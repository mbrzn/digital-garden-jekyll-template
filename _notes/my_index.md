---
title: my_index
---
## Что делать
- [ ] `wav` файлы
	- [ ] обертка
		- [ ] **?** копирование в `asset`
		- [ ] **?** симлинк на директорию?
- [ ] `png` файлы
	- [ ] обертка
		- [ ] **?** копирование в `asset`
		- [ ] **?** симлинк на директорию?
- [ ] `dvju` файлы
	- [ ] обертка
		- [ ] **?** копирование в `asset`
		- [ ] **?** симлинк на директорию?
## Объекты для оформления
### Объект 1

[[obj1]]
### Объект 1

[[obj2]]

## Документы для оформления
### wav
![[assets/audio3.wav]]


../../assets/audio3.wav


#### [How to embed audio into a Jekyll blog?](https://stackoverflow.com/questions/63701944/how-to-embed-audio-into-a-jekyll-blog)
>[How to embed audio into a Jekyll blog? - Stack Overflow](https://stackoverflow.com/questions/63701944/how-to-embed-audio-into-a-jekyll-blog)
>I would like to embed a simple audio player into one of my posts, in order to allow the reader to play a short .wav file.

```
# _include/embed-audio.html
<audio controls>
  <source src="{{ include.src }}" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>

# Use in the post as
{% include embed-audio.html src="/assets/audio/<audio-source-name>.wav" %}
```




### mp3

![[_notes/objects/obj1/audio3.mp3]]
### pdf I
![[elibrary_21705789_91483895.pdf]]
### rtf
![[stolbcy.rtf]]
### djvu
![[Yaremchuk_vtoraya_zhizn_starykh_kompyuterov.djvu]]
### epub
![[Бураттини. Фашизм прошел.epub]]
### pdf II
![[Левкипп и Демокрит. Часть 2. Популяризация учения.pdf]]
