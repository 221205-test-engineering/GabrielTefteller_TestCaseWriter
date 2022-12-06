signup-form.html Test Suite *Please view as Raw text*.

|| ============================================================================================================================================================================ ||
|| Test Case || Desc                         || Steps                                                                                                                           ||
|| ============================================================================================================================================================================ ||
|| TC-1      || fully correct credentials    || Enter username "Jonas2", enter password as "Pizza3", press the "submit" button, check for redirection                           || 
|| TC-2      || correct matching credentials || Enter username "Jonas2", enter password as "Jonas2, press the "submit" button                                                   ||
|| TC-3      || No Numbers                   || Enter username "JoeJonas", enter pass as "BigPizza", press "submit"                                                             ||
|| TC-4      || No Lowercase                 || Enter username "JONAS2", enter pass as "PIZZA3", press "submit"                                                                 ||
|| TC-5      || No Capitals                  || Enter username "jonas2", enter pass as "pizza3", press "submit"                                                                 ||
|| TC-6      || Correct user, wrong pass     || Enter username "Jonas", enter pass as "pizza"                                                                                   ||
|| TC-7      || Wrong user, correct pass     || Enter username "joejonas", enter pass as "Pizza3"                                                                               ||
|| TC-8      || User too long                || Enter username "bigJoeJonas365", enter pass as "Pizza3"                                                                         ||
|| TC-9      || Pass too long                || Enter username "Jonas2", enter pass as "timeToDeliverAPizzaBall69"                                                              ||
|| TC-10     || User too short               || Enter username "a2A", enter pass as "Pizza3"                                                                                    ||
|| TC-11     || Pass too short               || Enter username "Jonas2", enter pass as "a2A"                                                                                    ||
|| TC-12     || John                         || Enter any username with "John" in it, enter pass as "Pizza3"
|| ============================================================================================================================================================================ ||

|| ==================================================== ||
|| Test Case || Desc                          || Status ||
|| ==================================================== ||
|| TC-1      || fully correct credentials     || F      || *All passes from here on ignore TC-1
|| TC-2      || correct matching credentials  || F      || 
|| TC-3      || No Numbers                    || P      ||  
|| TC-4      || No Lowercase                  || P      ||          
|| TC-5      || No Capitals                   || P      ||          
|| TC-6      || Correct user, wrong pass      || P      ||
|| TC-7      || Wrong user, correct pass      || P      ||
|| TC-8      || User too long                 || P      ||
|| TC-9      || Pass too long                 || P      ||
|| TC-10     || User too short                || P      ||
|| TC-11     || Pass too short                || P      ||
|| TC-12     || John                          || F???   ||
|| =====================================================||