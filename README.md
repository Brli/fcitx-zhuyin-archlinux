# fcitx-zhuyin-archlinux
PKGBUILD files for Arch Linux user to test around, currently broken.

## libpinyin
    
    - fetch from my fork of [libpinyin](https://github.com/Brli/libpinyin)
    
    - check [commits](https://github.com/Brli/libpinyin/commits/master) for detail
    
    - mainly patching broken libzhuyin during merging from independent repo.
    
    - `fix-missing-libzhuyin-symbol.patch` is from https://github.com/libpinyin/libpinyin/pull/130
    
    - may clean up and PR upstream in the near future.
    
## fcitx-zhuyin
    
    - fetch from my fork of [fcitx-zhuyin](https://github.com/Brli/fcitx-zhuyin)
    
    - patch to modernize with upstream API change
    
    - **FIXME** currently crash when input, display no bopomofo...

