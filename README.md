# Dart: Handling Non-Existent Keys in JSON Response

This repository demonstrates a common error in Dart when handling JSON responses and provides a solution.

## The Problem

When parsing JSON data in Dart, attempting to access a key that doesn't exist in the JSON object will throw an exception, potentially crashing your application.

The `bug.dart` file shows an example of this problem.  It attempts to access the `'name'` key, which may or may not be present in the JSON response.

## The Solution

The `bugSolution.dart` file provides a solution by checking for the key's existence before accessing it.

This is accomplished using the `containsKey()` method of the Map object and provides a more robust and error-tolerant way of handling JSON responses.
