# sortorder [![PkgGoDev](https://pkg.go.dev/badge/github.com/Hunted-Labs/sortorder)](https://pkg.go.dev/github.com/Hunted-Labs/sortorder)

    import "github.com/Hunted-Labs/sortorder"

Sort orders and comparison functions.

Case-insensitive sort orders are in the `casefolded` sub-package
because it pulls in the Unicode tables in the standard library,
which can add significantly to the size of binaries.
