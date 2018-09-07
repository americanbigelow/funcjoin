# funcjoin

This is still in it's infancy.

It's a tool to compile together a group of functions from other scripts. Ideally, one will copy any function they compose into it's own script upon creation for future use. Then this tool can be used to join those together into a group of functions at the top of a new script whenever needed. This is similar to the way code from various libraries can be added to source in c.

The tool will gab all of a function body from the declaration to the closing "}". With that said, functions should be created with all comments between these vertical boundaries if this tool will be used.
