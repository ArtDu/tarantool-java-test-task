Тестовое задание:

1. Запустить тесты [ShipTest.java](src/test/java/io/tarantool/springdata/example/repository/ShipTest.java)
2. Реализовать тест `testSaveAndFind`.  
   Тест должен записывать `tuple` в tarantool(проверяя успешно ли прошла запись) и далее делать запрос select запрос в tarantool для проверки, что мы можем получить запись, которую записали insert'ом.
3. Написать дополнительные тесты покрывающие работу Java и Tarantool.

*Дополнительные задания:
4. Изменить входные данные `tuple` таким образом, чтобы `testEval` сломался (нельзя модифицировать модель Ship)
5. Починить тест