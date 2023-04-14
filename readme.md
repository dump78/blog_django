Запуск тестов:
python3 manage.py test

Изменение уровня логгирования(0, 1, 2, 3):
python3 manage.py test --verbosity 2

Запуск выбранных тестов:

python3 manage.py test catalog.tests   # Run the specified module
python3 manage.py test catalog.tests.test_models  # Run the specified module
python3 manage.py test catalog.tests.test_models.YourTestClass # Run the specified class
python3 manage.py test catalog.tests.test_models.YourTestClass.test_one_plus_one_equals_two  # Run the specified method