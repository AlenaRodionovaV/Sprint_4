# Юнит-тестирование. Финальный проект 4 спринта
## Список автотестов для класса BooksCollector()

<hr>

1. **test_set_book_genre_positive** - позитивный тест - при наличии книги в словаре `books_genre` ей присваивается жанр
2. **test_set_book_genre_negative** - негативный тест - если книги нет в словаре `books_genre`, то жанр ей не присваивается
3. **test_get_book_genre_positive** - позитивный тест - получаем жанр книги по её имени
4. **test_get_book_genre_negative** - негативный тест - не получаем жанр книги, т.к. её имя отсутствует в словаре `books_genre`
5. **test_get_books_with_specific_genre** - позитивный тест - выводится список книг только с определенным жанром
6. **test_get_books_genre_positive** - позитивный тест - выводится весь словарь `books_genre`
7. **test_get_books_for_children_positive** - позитивный тест - возвращаются книги, которые подходят детям
8. **test_add_book_in_favorites** - позитивный тест - книга добавляется в избранное
9. **test_delete_book_from_favorites** - позитивный тест - книга удаляется из избранного
10. **test_get_list_of_favorites_books** - позитивный тест - отображается список книг, занесенных в избранное