# CorporationX

Это проект над которым я работал вместе со своей командой из 8 человек. Писали проект на микросервисной архитектуре. Фичи реализованные мной будут указаны ниже.

# Мои фичи

Фича News Feed реализованная на event-driven подходе с low-latency, scalability и reliability, кешированием (Redis) и брокером сообщений Kafka
https://github.com/AntonRudnikovskiy/post_service/blob/medusa-master-Anton/src/main/java/faang/school/postservice/messaging/consumers/PostViewConsumer.java

Реализовал отдельный микросервис URL shortener для реферальной системы используя кэширование с помощью (Redis)
https://github.com/AntonRudnikovskiy/url_shortener_service/tree/medusa-master-Anton

Реализовал аналитику комментариев в отдельном микросервисе с брокером сообщений (Redis)
https://github.com/AntonRudnikovskiy/analytics_service/blob/medusa-master/src/main/java/faang/school/analytics/messaging/CommentEventListener.java

Разработал систему достижений  на event-driven архитектуре с брокером сообщений (Redis)
https://github.com/AntonRudnikovskiy/achievement_service/blob/medusa-master/src/main/java/faang/school/achievement/messaging/mentorship/MentorshipEventListener.java

Разработал уведомление запроса на менторство в отдельном микросервисе с брокером сообщений (Redis)
https://github.com/AntonRudnikovskiy/notification_service/blob/medusa-master/src/main/java/faang/school/notificationservice/messaging/MentorshipOfferedEventListener.java

Интегрировал Google Calendar в приложение, что позволило пользователям создавать и организовывать свои события
https://github.com/AntonRudnikovskiy/user_service/blob/medusa-master/src/main/java/school/faang/user_service/service/event/google/CalendarService.java

Реализовал отправку SMS-сообщений через Vonage API обеспечив пользователям надежную доставку уведомлений
https://github.com/AntonRudnikovskiy/notification_service/blob/medusa-master/src/main/java/faang/school/notificationservice/notification/SmsService.java

Интегрировал Amazon S3 для работы с media-файлами в 3+ микросервисах обеспечивая надежное хранение данных
https://github.com/AntonRudnikovskiy/user_service/blob/medusa-master/src/main/java/school/faang/user_service/config/amazon/AmazonConfig.java

Реализовал систему лайков для постов и комментариев, давая пользователям возможность выражать предпочтения
https://github.com/AntonRudnikovskiy/post_service/blob/medusa-master/src/main/java/faang/school/postservice/service/LikeService.java

Разработал сервис для добавления и удаления аватарок пользователей, давая им контроль над своим профилем
https://github.com/AntonRudnikovskiy/user_service/blob/medusa-master/src/main/java/school/faang/user_service/service/UserProfilePicService.java
