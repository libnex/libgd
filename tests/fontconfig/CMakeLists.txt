IF(FREETYPE_FOUND AND FONTCONFIG_FOUND)
LIST(APPEND TESTS_FILES
    basic
)
ENDIF(FREETYPE_FOUND AND FONTCONFIG_FOUND)

ADD_GD_TESTS()
