# OpenGLEmpty
> An empty project for OpenGL environment  
> using macOS  
> modified from https://github.com/JoeyDeVries/LearnOpenGL
## Mac OS X building
Building on Mac OS X is fairly simple:
```
brew install cmake assimp glm glfw freetype
cmake -S . -B build
cmake --build build -j$(sysctl -n hw.logicalcpu)
```

