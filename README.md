# nian
`Maybe mark down is a good way to keep diary?`

1. Quick note `Just for paste quickly :)`
   - Rename
    ```shell
    # Install HomeBrew and rename (Optional)
    ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
    brew install rename
    
    # Rename
    rename 's/(.*)-([^-]*)(\.*)/$2$3/' *
    ```
   - Replace image path
    ```
    http://img.nian.so/dream to https://github.com/memetoo/nian/raw/master/image/foder
    http://img.nian.so/step to https://github.com/memetoo/nian/raw/master/image/foder/process
    
    remove !dream
    remove !large
    ```

