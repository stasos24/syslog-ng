add_unit_test(CRITERION TARGET test_cfg_lexer_subst)
add_unit_test(CRITERION TARGET test_cfg_tree)
add_unit_test(CRITERION TARGET test_parse_number)
add_unit_test(CRITERION TARGET test_reloc)
add_unit_test(CRITERION TARGET test_hostname)
add_unit_test(CRITERION LIBTEST TARGET test_rcptid)
add_unit_test(CRITERION LIBTEST TARGET test_lexer)
add_unit_test(CRITERION LIBTEST TARGET test_pragma)
add_unit_test(CRITERION TARGET test_lexer_block)
add_unit_test(CRITERION TARGET test_str_format)
add_unit_test(CRITERION TARGET test_str-utils)
add_unit_test(CRITERION TARGET test_string_list)
add_unit_test(LIBTEST CRITERION TARGET test_runid)
add_unit_test(CRITERION TARGET test_pathutils)
add_unit_test(CRITERION TARGET test_utf8utils)
add_unit_test(CRITERION TARGET test_userdb)
add_unit_test(LIBTEST CRITERION TARGET test_logqueue)
add_unit_test(CRITERION TARGET test_cache)
add_unit_test(CRITERION TARGET test_scratch_buffers)
add_unit_test(CRITERION TARGET test_messages)
add_unit_test(CRITERION TARGET test_atomic_gssize)
add_unit_test(CRITERION TARGET test_window_size_counter)
add_unit_test(CRITERION TARGET test_apphook)
add_unit_test(CRITERION TARGET test_dynamic_window)
add_unit_test(CRITERION TARGET test_logsource)
add_unit_test(CRITERION LIBTEST TARGET test_persist_state)

SET_DIRECTORY_PROPERTIES(PROPERTIES
  ADDITIONAL_MAKE_CLEAN_FILES
  "test_values.persist;test_values.persist-;test_run_id.persist;test_run_id.persist-")
