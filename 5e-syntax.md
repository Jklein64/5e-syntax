I created this [[Visual Studio Code]] extension using [[JavaScript]] (well technically [[TypeScript]]) to enable syntax highlighting for the special additions within strings in [[5eTools]] [[JSON]] files.

This was my first [[Visual Studio Code|VSCode]] extension, and I learned a lot.  There is a lot of engineering and layers that go behind something as big as vscode, and the extension interface is really messy (well I wouldn't call it *messy* per se, but there are a lot of really long-named methods and a massive hierarchy of types that define things. I wouldn't want to be working on a project with it all the time, which hopefully isn't what software engineers do...).

Although the type hints are helpful and the docstrings in each of the functions are relatively thorough, the documentation on the website didn't really explain how to use all of the different types of extensions, so I made a different type by accident at first.

I also submitted my [first GitHub issue](https://github.com/microsoft/vscode/issues/110058), which was about the snippets aspect of the extension.  It got marked as a duplicate :facepalm: