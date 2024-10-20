# Byndyusoft-test

Тест падает по таймауту при попытке перейти на сайт Byndyusoft. 

При этом в консоли DevTools следующая ошибка:
`Uncaught SecurityError: Failed to set the 'domain' property on 'Document': Assignment is forbidden for sandboxed iframes.`

Пробовала добавить в конфигурационный файл cypress строку для обхода правил безопасности `chromeWebSecurity: false` но это не помогло. 
