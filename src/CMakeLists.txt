add_executable(sfml-test
	main.cpp
)

#link
target_link_libraries(sfml-test -lsfml-graphics -lsfml-window -lsfml-system)