package(default_visibility = ["//visibility:public"])

java_binary(
  name = "helloworld_graphqlserver",
  main_class="com.google.api.graphql.examples.helloworld.graphqlserver.GraphQlServer",
  data = glob(["resources/*"]),
  runtime_deps = [
    "//examples/java/com/google/api/graphql/examples/helloworld/graphqlserver",
  ],
)


java_binary(
  name = "library_graphqlserver",
  main_class="com.google.api.graphql.examples.library.graphqlserver.GraphQlServer",
  data = glob(["resources/*"]),
  runtime_deps = [
    "//examples/java/com/google/api/graphql/examples/library/graphqlserver",
  ],
)