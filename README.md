# JAVA




package com.bookapp.service;

public interface BookService {
	List<Book> getAllBooks();
	List<Book> getByAuthor(String author);
	Book getById(int id);
	List<Book> getByCategory(String category);
}
