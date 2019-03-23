# case-study-Wwwzff
Case Chosen: OpenCV

## Technology and Platform used for development
a). OpenCV(Open source computer vision), coded in C++, is an open source library originally developed by Intel and is initially released in 2000. For my opinion, if I'd started these functions today I'd like to chose python for its convenience when dealing with image datas. Since Python is not a strong type as C++ or Java, it has more flexibility especially calling build-in data structures like list or dictionary, which is obvious easier comparing to map/vector in C++, which also means time saving when coding basic library functions. Besides, taking python's popularity to programmers into account, a python based project means more references and more mature help/suggestions from third party. 

b). CMake's used when building the whole system. Although all algorithms are implemented in C++, OpenCV's actually supporting other languanges like Python(OpenCV-Python) and Java(OpenCV.js). Take python for example, according to their tutorial, a automatic wrapper script in modules/python/src2 wrap C functions automatically and thus there's no need to rewrite whole code in python at all. See [How OpenCV-Python Bindings Works](https://docs.opencv.org/4.0.1/da/d49/tutorial_py_bindings_basics.html)

C++ and Python version are both built using simple GCC compiler. For the java version, a compiler called [Emscripten](https://github.com/emscripten-core/emscripten)'s taking the job. There's also another library called [Binaryen](https://github.com/WebAssembly/binaryen) needed for compiling to webassembly. See [Build OpenCV.js](https://docs.opencv.org/4.0.1/d4/da1/tutorial_js_setup.html)
