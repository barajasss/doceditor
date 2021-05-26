# Doc Editor
Application code for the MERN stack youtube video.

VIDEO LINK: https://youtu.be/dtLXZEuZbeQ

DESCRIPTION (Copied from video)

TIP: You can improve the application by adding features like:
a) Edit dropdown with options like cut, copy, paste, undo, redo, etc. All these can be achieved using execComand() API.
b) Adding more editing options like justify text, add headings, background colors, etc. to experiment more.

*1. Github link for the project (final code as per the video):*
https://github.com/barajasss/doceditor

*2. html2pdf JS link:*
https://raw.githack.com/eKoopmans/html2pdf/master/dist/html2pdf.bundle.js

*3. execCommand() docs:*
https://developer.mozilla.org/en-US/docs/Web/API/Document/execCommand

*Notes*

execCommand() is deprecated but there is no other suitable alternative API to achieve this using vanilla javascript and it is very difficult. 
So until the proper alternative solution for execCommand() comes out, you have to use that. 

For professional projects, I recommend you explore other third-party libraries for rich text editing. They are great, easy, and simple to integrate. Quill JS is a good example (open source): 
https://quilljs.com/
 
This video was intended to show the features of vanilla javascript and achieving using just that.

Q: What is the main difference between a div with content editable and a textarea?

Ans: A div element will expand its height itself when you will click enter or content increases. However, a textarea element has a fixed height and it uses a scrollbar to show the overflowing contents. When you use div with content editable property, you can also apply all the styling that is possible on a normal div.

For more information on it, read this stackoverflow post:

https://stackoverflow.com/questions/5284193/what-are-the-cons-of-using-a-contenteditable-div-rather-than-a-textarea#:~:text=The%20advantage%20of%20a%20textarea,of%20all%20that%20for%20you.&text=It's%20not%20the%20same%20thing,the%20behavior%20is%20also%20different.

Like, Comment, And Subscribe to the MERN stack!
