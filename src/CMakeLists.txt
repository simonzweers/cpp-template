
list(
	APPEND sources
	"main.cpp"
	"example.cpp"
)

add_executable(${PROJECT_NAME} ${sources})

target_link_libraries(
	${PROJECT_NAME}
	spdlog::spdlog
)
