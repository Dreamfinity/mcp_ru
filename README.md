[![help](github_media/google_forms_badge.svg) ](https://forms.gle/aSPPBVSRidogo87J6)
# <img src="github_media/logo.png" alt="logo"/>
**mcp_ru** - Рускоязычные маппинги для MCP 1.7.10

Содержит осмысленные имена переменных и методов для исходного кода Minecraft, не включенных в официальный маппинг, а так же javadoc-документацию на русском языке.

## Установка:
1. Добавьте репозиторий проекта в ваш `build.gradle` (убедитесь что вы НЕ внутри блока `buildscript{}`):
```gradle
repositories {
    maven {
        url = "https://dl.bintray.com/rarescrap/minecraft"
    }
}
```
2. Укажите вариант маппингов для использования
```gradle
minecraft {
    ...
    mappings = "ru_snapshot_custom"
}
```
3. Выполните `gradlew setupDecompWorkspace`

## Запланированные фичи
1. [ ] Несколько каналов маппингов по образу и подобию официальных:

| Канал маппингов    |  Описание                                                                                                                                                                         |
|--------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ru_stable          | * Параметрам методов даны осмысленные названия<br>* Исключены методы и поля, не включенные в стандартный стабильный маппинг<br>* Русский Javadoc на всех классах, методах и полях |
| ru_stable_nodoc    | ru_stable, но без каких либо javadoc'ов                                                                                                                                           |
| ru_stable_stddoc   | ru_stable, но только с английскими javadoc'ами из стандартного стабильный стабильного маппинга                                                                                    |
| ru_snapshot        | * Параметрам методов даны осмысленные названия<br>* Всем методам и полям даны осмысленные названия<br>* Русский Javadoc на всех классах, методах и полях                          |
| ru_snapshot_nodoc  | ru_snapshot, но без каких либо javadoc'ов                                                                                                                                         |
| ru_snapshot_stddoc | ru_snapshot, но только с английскими javadoc'ами из стандартного стабильный стабильного маппинга                                                                                  |

2. [ ] CI для автоматического билда маппингов при поступивших коммитах

## Внесите свой вклад
Написали джавадок для кода игры или дали осмысленные имена переменным в переопределенном методе? Вы можете поделиться им с нами без создания пулреквестов или исьюсов. Просто воспользуйтесь нашей [гугл-формой](https://forms.gle/aSPPBVSRidogo87J6).

При наличии гитхаб аккаунта вы можете сдель пулреквест и ваше имя отобразится в таблице внесших свой вклад.

## Вклад внесли
1. RareScrap
2. **вы?**
