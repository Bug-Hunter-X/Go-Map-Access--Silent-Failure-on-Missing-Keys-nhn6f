# Go Map Access: Silent Failure on Missing Keys

This example demonstrates a common issue in Go where accessing a non-existent key in a map does not cause a panic or an error, but instead silently returns the zero value for the map's value type.

This can be problematic because it makes it easy to introduce subtle bugs that are hard to detect.

The `bug.go` file contains code that demonstrates the issue. The `bugSolution.go` file contains a possible solution.
