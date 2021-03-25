**Associations!**

We have courses, users, and enrollments.

A course can have many enrolled students, and a student can be enrolled to many courses. The bridging model (and db table) is Enrollment. A course can also have prerequisites, which are other courses that you need to take first. And it has an instructor. Using the above 3 models, we should be able to create all these associations. Should be fun!
