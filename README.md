VimRepress Extension
====================

This is a extension of **VimRepress**. 

VimRepress is a plugin for managing wordpress blog from Vim,  a rewritten  of vimscript #1953 , which is broken for years. See

    http://www.vim.org/scripts/script.php?script_id=3510

Now **VimRepressEx** use **Pygments** to prettify source code, see

	http://pygments.org

## Installation

To install using Vundle, add this line to your `.vimrc` file:

	Plugin 'joywek/VimRepressEx'

To install using pathogen.vim:

	cd ~/.vim/bundle
	git clone https://github.com/mattn/emmet-vim.git

## Command Examples

Some commands list above contain special usage, example below may clearify them for you. 

    :BlogList             -  List 30 recent posts. 
    :BlogList page        -  List 30 recent pages. 
    :BlogList post 100    -  List 100 recent posts. 

    :BlogNew post         -  Write an new post. 
    :BlogNew page         -  Write an new page. 

    :BlogSave             -  Save (defautely published.) 
    :BlogSave draft       -  Save as draft. 

    :BlogPreview local    -  Preview page/post locally in your browser. 
    :BlogPreview publish  -  Same as `:BlogSave publish' with brower opened. 

    :BlogOpen 679 
    :BlogOpen http://your-first-blog.com/archives/679 
    :BlogOpen http://your-second-blog.com/?p=679 
    :BlogOpen http://your-third-blog.com/with-your-custom-permalink 

More detailed about this commands, type :help vimpress while you have vimrepress installed. 


