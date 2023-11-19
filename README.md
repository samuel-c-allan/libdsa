# What is this?

This is a data structures and algorithms "library" I build simply for personal educational value.

Although I will keep it publically available and if anyone should find it useful all the better.

I use GoogleTest for test cases

# How to build?

For normal build:

`cd bin && cmake ..`

If you wish to build with unit tests:

`cd bin && cmake -D ENABLE_TESTING=ON ..`

# How may I collaborate?

If you see algorithms implemented in generally inefficient ways or wish to make the test cases better,
feel free to open an issue and create a PR if the issue receives general positive feedback.

Most content is welcome though I must warn you, these topics are difficult to convince me on:
 - **Extreme microoptimization or optimization for specific use cases**. This is mostly an education DSA repository so very specific use cases are off-limits, especially when they obscure the code
 - **Using templates very generally**. If you seek to use very general templating like in the STL you are better off using a library similar to STL. The purpose of this project is still primarily education. While some things are templated no effort is made to make routines as general as possible



