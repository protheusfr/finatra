create_thrift_libraries(
  base_name='echo-thrift',
  sources=globs('*.thrift'),
  generate_languages=["scala"],
  dependency_roots=[
    'finatra/thrift/src/main/thrift:thrift'
  ],
  provides_scala_name='echo-thrift-scala'
)
