# hlf_go_pkg

split go_dep.zip -b 32M go_dep_ZIPCHUNKS

cat go_dep_ZIPCHUNKS* > reassembled-go_dep.zip
