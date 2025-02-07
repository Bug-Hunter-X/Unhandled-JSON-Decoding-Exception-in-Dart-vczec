# Unhandled JSON Decoding Exception in Dart

This repository demonstrates a common error in Dart: failing to handle exceptions that can occur during JSON decoding using the `jsonDecode` function from the `dart:convert` library.

The `bug.dart` file shows the problematic code. The `bugSolution.dart` file provides a corrected version that gracefully handles potential `FormatException` exceptions.

This example highlights the importance of robust error handling in asynchronous operations, especially when dealing with external data sources that might return unexpected or malformed data.