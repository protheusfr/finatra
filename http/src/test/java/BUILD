junit_tests(
  name='java',
  dependencies=[
    '3rdparty/jvm/com/google/inject:guice',
    '3rdparty/jvm/junit',
    'finatra/http:test-deps',
    'finatra/httpclient',
    'finatra/inject/inject-server:test-deps'
  ],
  fatal_warnings=False,
  sources=rglobs(
    'com/twitter/finatra/integration/*.java',
    'com/twitter/finatra/test/*.java',
  ),
  resources=[
    'finatra/http/src/test/resources'
  ]
)
