This vim plugin makes "tab" honor "expandtab" for indents and always use spaces for alignment.

It will also auto-align to parentheses in C, C++, and Python. For example, given:

    ▷   ▷   def function(argument,▊argument):

pressing enter will result in:

    ▷   ▷   def function(argument,
    ▷   ▷                argument):
    
It's still pretty stupid, but it works. Install in plugin/smarttab.vim
