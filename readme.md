# glslCodeLite_lexers

Is a syntax highlighter lexer for **GLSL** (OpenGL Shading Language) to use with/in **CodeLite** cross platform IDE.

It covers until ver. 4.6 of **GLSL** and adds syntax highlighting to following file extensions:

 - `.glsl` → generic shader
 - `.vert` → vertex shader
 - `.frag` → fragment shader
 - `.geom` → geometry shader
 - `.tesc` → tessellation control shader
 - `.tese` → tessellation evaluation shader
 - `.comp` → compute shader
 - `.vs` → vertex shader
 - `.fs` → fragment shader
 - `.gs` → geometry shader
 - `.ts` → generic tessellation shader



![](https://raw.githubusercontent.com/BrutPitt/glslCodeLite_lexers/master/screenShot.jpg)

An *Obsidian* theme example, in ScreenShot, but syntax highlight is provided for all **CodeLite** themes

**Tested in **CodeLite** 14.0*

### How to Use
To use it, just add the `glslCodeLite_lexers.json` file content to `lexers.json` file in your config **CodeLite** folder, following/paying attention to `json` syntax:

**Windows**: `{user}\AppData\Roaming\codelite\lexers\lexers.json`

**Linux**: `~/.codelite/lexers/lexers.json`

