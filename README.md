# qa_python
В рамках тестов были проведены следующие проверки:

test_add_new_book_add_two_books_positive_result - проверка добавления в список 2 книг;
test_set_book_genre_is_comedy_positive_result - проверка установки жанра для книги;
test_get_book_genre_missing_book_return_null - проверка получения пустого списка, если запрашивается жанр книги, 
которая отсутствует в словаре;
test_get_books_with_specific_genre_add_book_and_genre_positive_result - проверка вывода книги в списке по жанру, 
если предварительно ее добавить;
test_get_books_genre_book_with_new_genre_return_not_None - проверка добавления книги с неизвестным жанром выводит не пустой список;
test_get_books_for_children_horror_book_not_added_to_children_books - проверка жанр книг ужасов не записывается в список детских книг;
test_add_book_in_favorites_re_adding_books_false - проверка добавления книги в список избранного, в котором она уже присутствует;
test_delete_book_from_favorites_added_1_book_is_deleted_from_favorites - проверка удаления книги из избранного, 
которая предварительно была добавлена;
test_get_list_of_favorites_books_without_added_book_return_empty_list - проверка дефолтного состояния избарнного - список пустой, 
если в него ничего не добавляли.