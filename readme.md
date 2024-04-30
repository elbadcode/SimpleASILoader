## Simple ASI Loader
- Simple hijackable dll that loads ASI modules/plugins.
- Any `.asi` file in process/plugins/scripts directory will be automatically loaded at launch of the hijacked dll (ASI Loader).

#### Supported DLLs
- version [(x64)](https://github.com/sneakyevil/SimpleASILoader/releases/tag/version_x64) [(x86)](https://github.com/sneakyevil/SimpleASILoader/releases/tag/version_x86)
- vorbisfile [(x86)](https://github.com/sneakyevil/SimpleASILoader/releases/tag/vorbisfile)

#### Compiling
- Visual Studio 2019 or later
- Clang Compiler (LLVM)

#### Preprocessor Defines
- EXPORTS_ALL (Exports everything)
- EXPORTS_VERSION
- EXPORTS_VORBISFILE