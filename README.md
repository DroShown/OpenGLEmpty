# OpenGLEmpty

> An empty project for OpenGL environment  
> using macOS  
> modified from https://github.com/JoeyDeVries/LearnOpenGL

## Mac OS X building

```
brew install cmake assimp glm glfw freetype
cmake -S . -B build
cmake --build build -j$(sysctl -n hw.logicalcpu)
```

