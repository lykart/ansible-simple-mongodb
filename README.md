# ansible-simple-mongodb
Самая простоя конфигурация mongodb  с 1м мастером и 2мя репликами 

Для установки тег install_mongodb, для настройки deploy_config

В инвентарнике группа для хостов mongodb, в type - mongod

В переменной type mongodb_master - для мастер ноды

В переменных можно указывать не стандартный порт монги, приоритет 
