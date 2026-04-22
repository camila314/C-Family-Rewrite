# C-Family-Improved
C family (C, C++, Objective-C, Objective-C++) syntax rewrite for Sublime Text.

This is a standalone version of the [Pull Request](https://github.com/sublimehq/Packages/pull/4147). 

## Changes made to C Highlighting
- Removed `#if 0` and `#if 1 #else` creating a commented out block
- Added `i` and `j` to numerical suffixes (GNU extension)
- Add `_Alignof`, `alignof`, and `offsetof`, `_Static_assert`, `static_assert`, `_Pragma` as word operators
- Every double-underscored identifier without another scope is treated as support constant
- `__cplusplus` is a `support.constant`
- Add `nullptr_t` (C23) and `max_align_t` (C11) to list of default types
- Add `_Thread_local`, `thread_local`, `_Atomic`, `_Alignas` and `_Noreturn` as storage modifiers
- Fixed bug where a function parameter followed by a newline wouldn't be highlighted properly
- Add more `__declspec` properties
- Add common `__attribute__` properties
- Add digit separator `'` (C23)
- Add scopes for `__VA_ARGS__` and `__VA_OPT__` (C23)
- Give defined macro a `suport.macro.c` scope
- Add `#embed`, `#elifdef`, and `#elifndef` directives (C23)
- Add multi-line double-slashed comments via `\`
- Add `typedef` support for function ptrs
- Function pointer arguments in a `typedef` now share the same scoping as regular function defs

## Issues
- [x] Fixes sublimehq/Packages#4104
- [x] Fixes sublimehq/Packages#4058
- [x] Fixes sublimehq/Packages#4104
- [x] Fixes sublimehq/Packages#3956
- [x] Fixes sublimehq/Packages#3938
- [x] Fixes sublimehq/Packages#3901
- [x] Fixes sublimehq/Packages#3805
- [x] Fixes sublimehq/Packages#3592
- [x] Fixes sublimehq/Packages#3504
- [x] Fixes sublimehq/Packages#3317
- [x] Fixes sublimehq/Packages#3224
- [x] Fixes sublimehq/Packages#2815
- [x] Fixes sublimehq/Packages#2762
- [x] Fixes sublimehq/Packages#2334
- [x] Fixes sublimehq/Packages#2221
- [x] Fixes sublimehq/Packages#2047
- [x] Fixes sublimehq/Packages#1830
- [x] Fixes sublimehq/Packages#1438
- [x] Fixes sublimehq/Packages#1138
- [x] Fixes sublimehq/Packages#1093 
- [x] Fixes sublimehq/Packages#1070
