load("@rules_java//java:defs.bzl", "java_binary")

java_binary(
    name = "app",
    srcs = ["src/main/java/com/greeting/App.java"],
    main_class = "com.greeting.App",
    deps = [":greeter"],
)

java_library(
    name = "greeter",
    srcs = ["src/main/java/com/greeting/Greeting.java"],
)
