foreach(
    example
    prioritised_handlers
)
boost_add_executable(
    ${example}
    DEPENDS
    boost_system
)
endforeach(
)
