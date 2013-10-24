Autotest
========

This is based on the wonderful tool "pta" (https://github.com/remogatto/prettytest/tree/master/pta)

I liked this tool and used it a lot while learning Go.

It had two problems I felt.

1) It came packaged with a test formatter / runner suite that I didn't use
2) Everytime I had a project with a directory of assets that didn't include Go code, I'd get a bunch of unneccessary error messages in stdout

This version fixes that and will only watch directories and run `go test` on directories that contain go tests
