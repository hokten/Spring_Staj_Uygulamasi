package com.tbmyo.staj.controller;

import org.springframework.web.bind.annotation.GetMapping;
import org.springframework.web.bind.annotation.RestController;
import java.util.ArrayList;
import java.util.List;
import lombok.Data;
import com.tbmyo.staj.entities.Student;

@RestController
public class BookController {

	@GetMapping("/books")
	public List<String> getBooks() {
		final List<String> books = new ArrayList<String>();
		Student deneme = new Student();
	    
		books.add("A Little Forever");
		books.add("To Kill a Mockingbird");
		books.add("A Thousand Splendid Suns");

		return books;
	}

	@GetMapping("/secured/books")
	public List<String> securedBooks() {
		final List<String> books = new ArrayList<String>();
		books.add("Harry Potter and the Philosopher's Stone");
		books.add("Harry Potter and the Chamber of Secrets");

		return books;

	}
}
