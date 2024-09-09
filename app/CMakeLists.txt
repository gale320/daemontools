add_executable(chkshsgr chkshsgr.c)
target_link_libraries(chkshsgr daemontool)

add_executable(envdir envdir.c)
target_link_libraries(envdir daemontool)


#fghack.c    pgrphack.c       setlock.c    softlimit.c  svc.c   

add_executable(fghack fghack.c)
target_link_libraries(fghack daemontool)

add_executable(pgrphack pgrphack.c)
target_link_libraries(pgrphack daemontool)

add_executable(setlock setlock.c)
target_link_libraries(setlock daemontool)

add_executable(softlimit softlimit.c)
target_link_libraries(softlimit daemontool)

add_executable(svc svc.c)
target_link_libraries(svc daemontool)

#vscan.c  tai64n.c envuidgid.c  multilog.c  readproctitle.c 
add_executable(svscan svscan.c)
target_link_libraries(svscan daemontool)

add_executable(tai64n tai64n.c)
target_link_libraries(tai64n daemontool)

add_executable(envuidgid envuidgid.c)
target_link_libraries(envuidgid daemontool)

add_executable(multilog multilog.c)
target_link_libraries(multilog daemontool)

add_executable(readproctitle readproctitle.c)
target_link_libraries(readproctitle daemontool)

# setuidgid.c  supervise.c  svok.c  svstat.c  tai64nlocal.c
add_executable(setuidgid setuidgid.c)
target_link_libraries(setuidgid daemontool)

add_executable(supervise supervise.c)
target_link_libraries(supervise daemontool)

add_executable(svok svok.c)
target_link_libraries(svok daemontool)

add_executable(svstat svstat.c)
target_link_libraries(svstat daemontool)

add_executable(tai64nlocal tai64nlocal.c)
target_link_libraries(tai64nlocal daemontool)
