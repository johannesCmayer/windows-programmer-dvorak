windows-programmer-dvorak
=========================

This is a modified version that contains the programmer layout for the igbo leanguage. This is to work around the problem that windows always adds a US layout to the US leanguage and switches seemingly at random bettween drovrak and normal US.

Contains the MS Keyboard Layout Creator source file for Programmer Dvorak (as found on [http://www.kaufmann.no/roland/dvorak/](http://www.kaufmann.no/roland/dvorak/)).

How is this better than the Windows driver provided on that site?

1. I use Microsoft's Keyboard Layout Creator to make a native solution. This means that the 10-key number pad layout will be preserved, rather than taking on the same key assignments as the number row.
2. The source file will be included. This means you will be able to customize and recompile the source to suit your needs. Note: compiling from source will require the [Keyboard Layout Creator](http://msdn.microsoft.com/en-us/goglobal/bb964665.aspx) from Microsoft. With the Layout Creator, you will then be able to redistribute your modifications via installer. Pretty slick.

Feel free to create pull requests with any changes.