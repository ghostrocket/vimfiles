This is my ~/.vim dir and _this_, dear reader, is a horse:

                   ,
                  / \,,_  .'|
               ,{{| /}}}}/_.'
              }}}}` '{{'  '.
            {{{{{    _   ;, \
         ,}}}}}}    /o`\  ` ;)
        {{{{{{   /           (
        }}}}}}   |            \
       {{{{{{{{   \            \          ,-------------------------------.
       }}}}}}}}}   '.__      _  |        /       HI                        \
       {{{{{{{{       /`._  (_\ /       /      /   \                        |
        }}}}}}'      |    //___/   --= <   VVVI     HI-HI-HI                |
    jgs `{{{{`       |     '--'         \                   \               |
         }}}`                            \                  HIM-HIM-HIM!!!  /
                                          '--------------------------------'

# Installation

Clone the repo:
`git clone https://github.com/ghostrocket/vimfiles.git ~/.vim`

Grab the plugin submodules:
`cd ~/.vim && git submodule update --init`

Make sure vim finds the vimrc file by symlinking it:
`ln -s ~/.vim/vimrc ~/.vimrc`

# Dependencies

The TagBar bundle requires ctags:
`brew install ctags`

The JSLint bundle requires node:
`brew install node`
