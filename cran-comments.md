Dear CRAN Team,

This is a documentation update only. There are NOTEs due to all functions
named as "binr.my_function", which the checker mistakenly thinks are S3 methods.
The only option I see is to rename the functions, which is not practical due to dependencies
on this package. Pretending that they are S3 methods only for documentation purposes
results in WARNINGs that the function signatures don't match the expected ones.

I hope this is a minor issue and the package can be accepted.

Thank you,
Sergei
