Смарт-Контракт для голосования.  
Основные функции приложения:  
 Создание голосования: Пользователи могут инициировать голосование.  
 Голосование за кандидатов: Приложение позволяет пользователям голосовать за кандидатов, основываясь на сессиях голосования.  
 Смена владельца голосования: Только владелец голосования может передавать управление.  
 Тестовые аккаунты: Возможность переключать аккаунты для тестирования функций.  
Методы контракта:  
 • createVotingSession(): Создание новой сессии голосования.  
 • vote(): Голосование за кандидата.  
 • transferOwnership(): Передача прав владельца.  
При запуске приложения появляется 5 кнопок, для голосования за 2 кандидатов, не смог полноценно реализовать систему голосования с передачей прав на создание, и право голоса, функция для просмотра текущего голосования должна работать.  
Сделаны тесты, фронт часть, deploy контракта, но не получилось связать контракт и фронт.
