# My .vim directory

After cloning, use:

  cd ~/.vim

  git submodule init

  git submodule update

  cd ~

  ln -s .vim/vimrc .vimrc


## Command-T

Command-T does not work on Debian 6 AFAIK.
On OSX Snow Leopard, use:

  cd ~/.vim/bundle/command-t

  rake make

to enable Command-T.

If you are using RVM, remember to go back to the system ruby for this step with:
  
  rvm use system

After making Command-T you can obviously go back to your normal Ruby.

## gist-vim

Remember to set your Github username and API token with:

  git config --global github.user Username
  
  git config --global github.token APIToken
