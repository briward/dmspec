# Hooks
This directory is used to store hook implementations that have been used by
the module. The include files within this directory should *not* contain business
logic and instead should call methods from classes in the **src** directory.

The files in this specification are here purely as an example of what *may* be
present in your module. The pattern for naming the include files is
`<your_module>.<package>.inc` ("package" should be either: the module the hook
originates from or a sensible name for the group of hooks it contains).
