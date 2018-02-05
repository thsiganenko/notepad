Использование плагина Emmet в Vim
================================================================================
[Source](https://raw.githubusercontent.com/mattn/emmet-vim/master/TUTORIAL)

                                                    More information: help emmet

Expand an Word
--------------------------------------------------------------------------------
Type the word and type '&lt;c-y&gt;;'.

    div

    <div></div>

Expand an Abbreviation
--------------------------------------------------------------------------------
Type the abbreviation as 'div>p#foo$\*3>a' and type '&lt;c-y&gt;,'.

    <div>
        <p id="foo1\"><a href=""></a></p>
        <p id="foo2\"><a href=""></a></p>
        <p id="foo3\"><a href=""></a></p>
    </div>

Wrap with an Abbreviation
--------------------------------------------------------------------------------
Write as below.
    
    test1
    test2
    test3

Then do visual select (line wise) and type '&lt;c-y&gt;,'.
Once you get to the "Tag:" prompt, type 'ul>li\*'.

    <ul>
        <li>test1</li>
        <li>test2</li>
        <li>test3</li>
    </ul>

If you type a tag, such as 'blockquote', the you'll see the following:

    <blockquote>
        test1
        test2
        test3
    </blockquote>

Go to the Next Edit Point
--------------------------------------------------------------------------------
Type '&lt;c-y&gt;n' in insert mode.

Go to the Previous Edit Point
--------------------------------------------------------------------------------
Type '&lt;c-y&gt;N' in insert mode.

Toggle Comment
--------------------------------------------------------------------------------
Move cursor inside the block
    
    <div>
        hello world
    </div>

Type '&lt;c-y&gt;/' insert mode

    <!-- <div>
        hello world
    </div> -->

Type '&lt;c-y&gt;/' in there again.

    <div>
        hello world
    </div>

