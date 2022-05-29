add_executable(sfml-test
	main.cpp
)

#link with SFML
find_package(SFML 2.5 
  COMPONENTS 
    system window graphics network audio REQUIRED)
target_link_libraries(sfml-test -lsfml-graphics -lsfml-window -lsfml-system)